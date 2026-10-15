# N1 repository instructions

Read `design.md` and relevant canonical references before creating or reviewing N1 UI. Published Figma content is not evidence of approval. Preserve approval labels and mark unsupported information as “Needs design review”.

## Source authority

- Figma defines approved design variables and visual component specifications.
- Frontend source defines implemented component APIs. This repository currently has no frontend application; do not invent APIs or introduce a framework to fill that gap.
- Approved Markdown defines usage rules, principles, accessibility requirements and UX writing. Distinguish authored guidance, verified observations and proposals.
- `skills/n1-design-system/SKILL.md` defines workflows. Reference design values rather than duplicating them there.
- When sources conflict, record both sources, identifiers and observation dates; obtain design or engineering review rather than silently choosing a new rule.

## Figma access and provenance

Use the official MCP endpoint `https://mcp.figma.com/mcp`. Before fresh MCP extraction, verify authenticated access to file `01imXcjljmBfqXhqFmv4kz` and node `915:56433`. A login or configured URL alone is insufficient. Treat Figma as read-only: never create, update, delete, upload or change Code Connect mappings. Retain file key, node ID, tool/API, observation date and evidence reference. Preserve variable names, IDs, aliases and modes; never infer missing units or semantic classifications.

## Editing and generation

- Human-maintained: `design.md`, `foundations/`, `patterns/`, root guidance, skill workflow references and `SKILL.md`. Automation must not overwrite these with generated or AI-authored guidance.
- Generated: `tokens/*.json`, `components/`, `audit/component-inventory.md`, `audit/component-documentation-coverage.md`, skill `references/system/` and `references/snapshot-manifest.json`. Change their evidence or generator, regenerate, and review the diff. Keep other audit reports authored unless explicitly labelled generated.
- Read `docs/maintenance.md` for regeneration and review. Refresh the skill snapshot after canonical reference changes; never edit bundled copies directly.
- Run `python3 scripts/validate_repository.py` before proposing a commit. Run `python3 scripts/package_n1_skill.py --zip` to build the ignored local `skill.zip` after validation.
- All updates require reviewable diffs. Never automatically merge changes or assert that validation establishes design approval or accessibility compliance.

These maintenance paths and commands apply in the source repository. Inside a self-contained skill installation, use its bundled `scripts/validate_package.py`; repository regeneration scripts are not runtime dependencies.

## Credentials and publishing

Never commit credentials, OAuth responses, personal access tokens, `.env` files or local authentication state. Do not log credential values. Raw Figma evidence and bundled references may contain confidential product content, screenshots or external asset URLs; passing validation is not publication clearance. Do not automatically upload packages or assets. Do not push, create remote pull requests or publish until the user supplies the destination and authorizes the action. Prefer existing configurations and keep documentation portable.
