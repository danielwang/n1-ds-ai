# N1 design-system skill validation

Validation date: 15 October 2026. Status: **passed** for the checks below. This is a packaged reference skill, not a deployed UI or a claim of source approval.

## Package contents

- [SKILL.md](SKILL.md) with valid `name` and `description` frontmatter, scoped invocation guidance, and separate generation/review workflows.
- [agents/openai.yaml](agents/openai.yaml) with display name, short description, and a default prompt naming `$n1-design-system`; normal implicit invocation remains enabled by default.
- [Bundled design entry point](references/system/design.md), foundations, patterns, nine token JSON files, 492 component documents, catalog index, coverage records, and linked provenance.
- [Snapshot manifest](references/snapshot-manifest.json): 662 copied source reference files with original/packaged SHA-256 hashes. Two documented adaptations replace repository-only regeneration instructions; guideline text and source data are preserved.
- Three Python 3.9+ standard-library helpers: component search, actual-member selection checking, and package validation. No credentials, host-specific paths, required external skill, or mandatory MCP connection are packaged.

## Checks performed

| Check | Result |
| --- | --- |
| Available skill-creator `quick_validate.py` | Passed frontmatter, name, description, and unfinished-scaffold checks |
| YAML parsing | Passed for SKILL frontmatter and OpenAI metadata |
| Bundled-reference integrity | Passed all 662 snapshot file hashes |
| Local links/anchors | Passed; targets remain within the skill directory |
| JSON integrity | Passed all bundled JSON, including duplicate-key and invalid-constant checks |
| Component catalog | All 492 source IDs, original names, property definitions, and document identities match retained evidence |
| Colour preservation | All 45 normalized colours round-trip to their retained source hex values |
| Search helper | Passed exact-name, exact-node-ID, no-match, bounded-results, invalid-limit, and independent-working-directory checks |
| Source decision checks | Button has no published `Focused` state; TextField does. Unexposed radius units remain unknown. No unsupported value was added |
| ZIP integrity and portability | Passed archive CRC, safe single-root paths, member/directory byte comparison, and isolated extraction validation |
| Validator failure detection | Passed: modifying a copied snapshot file causes integrity validation to fail |
| Subsequent Agent Settings scenario preflight | Missing executable frontend/library detected; no framework or replacement N1 components invented |
| Actual-member selection regressions | Passed 12 positive/negative cases, including rejection of separately valid options with no matching member |

Run `python3 scripts/validate_package.py` from this skill's directory to repeat the self-contained integrity checks. OpenAI YAML and frontmatter were also parsed with PyYAML during packaging; runtime helpers do not require it.

## Validation limits

The [source coverage limitations](references/system/audit/component-documentation-coverage.md) and [approval gaps](references/snapshot.md) remain explicit. Skill validation does not certify UX decisions, accessibility compliance, full token modes/aliases, source approval, or live client installation. The subsequent Agent Settings preflight compared three components with current read-only Figma metadata and checked source-colour contrast, but was blocked before UI implementation by the missing frontend/library. No independent subagent evaluation, UI rendering/accessibility test, or live installation in ChatGPT, Codex, or Claude was performed. Host support for optional metadata and script execution varies; the Markdown references remain available without running the helpers.

The ZIP contains one top-level `n1-design-system/` directory. Installation or activation in a client is separate from creating this distribution.

## Repository maintenance verification

The source repository additionally checks deterministic regeneration, canonical-to-bundle freshness and reproducible local ZIP builds. The standalone validator now derives expected catalog and colour counts from retained source data instead of fixed historical totals. This supports reviewed future updates without changing design values. Repository CI and packaging are maintenance tools, not runtime dependencies of this installed skill; no release or asset upload runs automatically.
