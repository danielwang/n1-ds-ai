# Publishing checklist

Current state: local preparation only. No remote push, GitHub publication or asset upload has been performed. Do not treat this checklist as authorization.

## Before the first push

- [ ] Owner supplies the exact GitHub organization/repository destination and approves the push.
- [ ] Owner approves visibility. Use a private repository until all source evidence and bundled content are cleared for public distribution.
- [ ] Review `sources/figma/`, all audit evidence, screenshots/base64 content, persona/product text, author information, temporary asset URLs, setup history and the duplicate evidence inside the skill snapshot for confidentiality. Remove or redact only through a traceable review and regenerate dependencies. Ignoring files does not remove them from Git history.
- [ ] Review redistribution rights for Figma content, typography, icons and third-party material. Choose an owner-approved licence if distribution is intended; none is selected here.
- [ ] Run an organization-approved secret scan of the working tree and any existing Git history. The built-in narrow pattern check is not a full secret or confidential-content scanner. Keep `.env`, authentication state and generated ZIP/checksum ignored.
- [ ] Run `python3 scripts/validate_repository.py`, then `python3 scripts/package_n1_skill.py --zip`. Review staged paths and diffs before committing. Do not blindly add local account configuration or generated binary packages.
- [ ] Confirm documented approval/coverage gaps remain visible. The current partial token snapshot and blocked frontend scenario must not be represented as complete or compliant UI.

## Configure the approved repository

- [ ] Assign real design and engineering maintainers; add CODEOWNERS with their actual GitHub identities. No placeholder account is assumed.
- [ ] Enable Actions with read-only default token permissions. Run **Offline validation** and configure it as a required status check, with reviewer approval and protected default branch/rulesets.
- [ ] Restrict workflow changes and review pinned actions/runner policy. PR validation uses no Figma secrets, privileged PR events, release jobs or artifact uploads.
- [ ] If draft-PR regeneration is desired, create `n1-maintenance` with required reviewers, allow authorized Actions-created PRs, then explicitly set `N1_ENABLE_UPDATE_PRS=true`. Keep it unset otherwise. Dispatch only on the default branch after authorization; it is restricted to private repositories.
- [ ] Validate the first hosted run and inspect logs/permissions. Test a no-change regeneration run, a reviewed generated-change branch, a stale-reference failure and a deliberately broken-link PR. GitHub execution has not been tested locally.
- [ ] Manually dispatch validation on bot-created proposal branches when `GITHUB_TOKEN` event suppression prevents PR checks. Do not bypass required checks.
- [ ] Implement and approve the separate [live Figma export pipeline](figma-sync.md) before adding credentials or a schedule. Current regeneration uses committed evidence only.

## Distribute an approved skill

- [ ] Review canonical and bundled reference diffs, approval labels, source hashes and local ZIP contents.
- [ ] Validate the extracted package and test discovery/invocation in each intended client. OpenAI metadata does not establish universal client compatibility.
- [ ] Share ZIP and trusted checksum only through the approved private distribution route. A public release, Pages deployment, plugin submission or asset upload requires separate authorization.
- [ ] Record the reviewed repository commit, package SHA-256, source observation dates, reviewers and known limitations in the release record. Retain the previous approved package for rollback.

## Ongoing maintenance

For each source update, follow [maintenance](maintenance.md), keep an attributable evidence diff and route design decisions through review. Reassess Figma access, API entitlement, source coverage and client compatibility rather than assuming the initial connection remains valid. Review dependency pins periodically in PRs. Never auto-merge documentation or quietly replace authored UX guidance.
