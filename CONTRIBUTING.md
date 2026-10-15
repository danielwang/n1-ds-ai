# Contributing

Read [AGENTS.md](AGENTS.md), [design.md](design.md) and the [maintenance procedures](docs/maintenance.md). Use a branch and describe the source, scope, evidence date, approval status and known gaps in every proposed change.

Update retained evidence through approved read-only access. Regenerate derived specifications rather than manually patching their values. Keep authored guidance changes separate and identify the approving designer or product owner; AI-generated guidance remains a proposal until reviewed. Never commit credentials or local account configuration.

Run `python3 scripts/validate_repository.py` and review the diff before a commit. CI runs the same offline checks. Explain token removals, alias/mode changes, component renames and approval changes explicitly. Require a design reviewer for visual/usage decisions and an engineering reviewer for API/tooling changes; maintainers must configure actual reviewers and branch rules after the destination is approved.

Do not upload evidence, screenshots, ZIPs or assets as workflow artifacts. Share only after confidentiality and licensing review. Remote pushes and pull requests require authorization for the chosen destination. See the [publishing checklist](docs/publishing-checklist.md).
