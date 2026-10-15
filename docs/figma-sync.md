# Figma synchronization plan

Status: **proposed REST pipeline; not enabled or authenticated**. The existing builders support retained MCP evidence only. No scheduled extraction, REST-to-token converter, OAuth application, secret or live export workflow is installed by this change. This distinction prevents a partial node snapshot from being presented as a complete variable library.

## Available now

Use official read-only Figma MCP sampling for targeted visual structure and source-attributed component documentation. Access must be verified against the file before fresh extraction. Offline builders, freshness checks, deterministic skill packaging and the opt-in draft-PR regeneration workflow are available; that workflow rebuilds committed evidence and does not query Figma. See [maintenance](maintenance.md).

Current node-scoped values do not expose a complete collection/mode/alias graph. Retain the existing partial snapshot and coverage labels until a broader export is independently verified. Empty groups are not evidence that Figma has no tokens.

## Proposed approved API route

Use Figma's official read-only `GET https://api.figma.com/v1/files/01imXcjljmBfqXhqFmv4kz/variables/local`. Figma documents this as available to full members of Enterprise organizations with `file_variables:read`. It returns local variables and remote variables used in the file. The published-variables endpoint omits modes and is insufficient for this export. See [official endpoint documentation](https://developers.figma.com/docs/rest-api/variables-endpoints/).

Confirm organizational authorization, Enterprise eligibility, account access, OAuth application approval and least-privilege scope before implementation. MCP OAuth success does not establish REST entitlement or grant permission to reuse MCP credentials. Use an approved OAuth integration; keep its access/refresh credentials in an organization-managed secret store or protected GitHub environment, never in this repository, logs, generated files or skill bundle. Do not invoke variable POST endpoints. If access is unavailable, request a designer-approved export through an approved Figma plugin/workflow and preserve its provenance; do not scrape credentials or flatten a screenshot into guessed tokens.

## Pipeline stages and contracts

1. **Read into local staging.** A trusted manual job on the approved default branch performs only the GET above, with a bounded timeout and bounded retry/backoff for transient failures. Honor rate limits; stop on authentication/permission errors. Block cross-host redirects, never print authorization headers/error bodies, and never persist authentication responses. Store raw variable data under ignored `.local/` initially. Record file key, endpoint, observed UTC time, requesting workflow commit, content SHA-256 and any returned version metadata. If the API supplies no immutable file revision, mark it unknown and label the observation window; do not invent a revision.
2. **Validate the retained response.** Reject API errors, malformed/duplicate-key JSON and non-finite values. Preserve all variable/collection IDs, original names/keys, `resolvedType`, `valuesByMode`, collection modes/defaults, remote flags, descriptions, scopes, code syntax and extension/inheritance fields. Check unique IDs, collection references, default/mode IDs and typed literals. Retain aliases as ID references and report unresolved external references, alias cycles, incompatible types and missing mode values. Extended collections require explicit inheritance-aware validation; never silently replace missing values. Remote variables used by this file are not an enumeration of every remote library.
3. **Produce a candidate and diff.** Write a new, content-addressed proposal under a reviewed `proposals/figma/<hash>/` path only after confidentiality clearance. Preserve the original export and separate provenance manifest. Diff by stable IDs and mode IDs against the last approved export, reporting names, types, collection/mode membership, changed values/aliases, removals and unresolved references. With no approved REST baseline, report “baseline unavailable” rather than claiming all entries are new. Exclude screenshots, arbitrary attachments, credential data and temporary asset downloads.
4. **Review the conversion contract.** Implement and test a separate importer before changing `tokens/*.json`. Use a DTCG-aligned mapping where types and units are proven. Keep original names and IDs in provenance; use ID-based paths or a reversible mapping for names that cannot safely be token keys. Preserve aliases and per-mode values through a documented mode-aware representation; never select a default mode silently. Figma FLOAT does not establish px, rem or another unit. Do not infer primitive/semantic classification from names alone. Text/effect styles may require approved read-only file/style endpoints or MCP evidence in addition to variables. Include collection inheritance, alias cycles, composed colours, unsupported types and external dependency fixtures in importer tests.
5. **Open a draft PR.** Validate candidate JSON and diff, then create a branch and draft PR with scope, provenance, coverage limits and explicit design-review questions. Never commit directly to the protected branch. Require design approval for values/classification and engineering approval for schema/runtime implications. A proposal may include generated candidate data; it must not rewrite human-authored `design.md`, principles, voice/tone or usage rules.
6. **Promote after approval.** On an approved branch, run the reviewed importer, keep the source export and update coverage, regenerate dependent documentation and skill references, then run all offline checks. Merge only through protected review. Build a local ZIP; release/upload remains a distinct authorized action with confidentiality review.

## Automation boundaries

| Safe to automate after authorization | Requires review or additional source |
| --- | --- |
| Read-only export, response validation and source hashes | Account/organization/API permission and export confidentiality |
| Stable-ID diff and candidate generation | Removals, renamed semantics, units and mode mapping |
| Existing deterministic builders and packaging | New importer/schema contract and source coverage claims |
| Draft PR creation and offline checks | Design approval, authored UX guidance and implementation APIs |
| Targeted link/JSON/source consistency checks | Visual review, interaction behavior, WCAG testing and public distribution |

Before enabling a live workflow, require an approved private repository, a protected environment with actual reviewers, an explicit dispatch confirmation and separate read-only Figma secrets. Validation on untrusted PRs must never receive these secrets. Start with manual runs; introduce a schedule only after the owner explicitly authorizes cadence and budget. Do not upload export artifacts or automatically publish packages. Stop and report a failed permission/export/validation step rather than replacing a good snapshot with empty data.

The prepared regeneration workflow is intentionally distinct from this proposed live pipeline. Its repository-variable gate must remain off until the owner supplies the GitHub destination and authorizes branch pushes. No Figma API credentials are needed for current offline maintenance.
