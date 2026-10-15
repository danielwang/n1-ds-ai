# N1 (nebulaONE) AI-readable design system

Source-attributed design documentation and a portable Agent Skill for N1, an AI platform for higher education. Start with [design.md](design.md), then consult the [component index](components/index.md) and [token coverage](tokens/README.md).

The current snapshot documents **492 published entries** (112 component sets and 380 standalone components), with partial detailed inspection. Tokens include **45 extracted colour values**, retained raw typography/radius definitions and metadata-only discoveries. Modes, aliases and complete library coverage remain unverified. Published content does not establish approval. See the [coverage audit](audit/component-documentation-coverage.md) and [documentation gaps](audit/documentation-gaps.md).

Source: [N1 Figma library](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=915-56433). Figma remains read-only. [Connection evidence](docs/setup/connection-status.md) records the last verification, not a guarantee of current authentication.

## Work locally

Python 3.9+ and Git are sufficient for offline checks and packaging; no third-party Python packages, frontend framework or Figma credentials are required.

```sh
python3 scripts/validate_repository.py
python3 scripts/package_n1_skill.py --zip
```

The first command checks token provenance, component specifications, local documentation links and anchors, required files, skill snapshot freshness, package integrity, Python syntax, maintenance regression tests and obvious credential patterns. It does not modify approved guidance or query Figma. The second creates `skill.zip` locally; it is ignored by Git and never uploaded automatically. Validation does not establish approval, confidentiality clearance, full DTCG conformance or WCAG compliance.

After deliberately editing canonical references:

```sh
python3 scripts/package_n1_skill.py
python3 scripts/validate_repository.py
python3 scripts/package_n1_skill.py --zip
```

Review canonical and bundled changes together. See [maintenance](docs/maintenance.md), [skill installation and use](docs/skill-installation.md), and the [Figma synchronization plan](docs/figma-sync.md).

## Repository map

| Path | Responsibility |
| --- | --- |
| [design.md](design.md), `foundations/`, `patterns/` | Authored guidance, approval status and entry points |
| `components/`, `tokens/` | Generated specifications and partial token data |
| `sources/figma/` | Evidence and source manifest; review confidentiality before sharing |
| `audit/` | Coverage, gaps, scenario results and maintenance validation |
| `skills/n1-design-system/` | Self-contained skill, helpers and generated reference snapshot |
| `scripts/`, `tests/` | Offline validation, deterministic packaging and regression tests |
| `.github/` | Read-only CI, gated draft-PR regeneration and review template |
| `docs/` | Setup history, maintenance, installation, sync plan and publishing checklist |

`skills/nebulaone/`, `adapters/`, `assets/` and `schemas/` are legacy staging/placeholders, not separate production packages. No frontend implementation or verified component API package is present; the [skill scenario report](audit/skill-test-report.md) records that limitation.

## Source authority and review

Figma defines variables and visual specifications. Frontend code defines implemented APIs. Approved Markdown defines usage rules, principles and UX writing. `SKILL.md` defines AI workflows. Resolve conflicts through design/engineering review with source links; do not infer undocumented rules.

[AGENTS.md](AGENTS.md) governs coding agents. Read [CONTRIBUTING.md](CONTRIBUTING.md) before updating generated files. CI validates pull requests without secrets. The optional update workflow is disabled until explicitly enabled in an approved private repository; it opens draft PRs and never merges or publishes packages.

## Publishing status

Prepared for repository review; **no push or publication is authorized or performed**. Destination, visibility, maintainers, licensing and confidentiality clearance remain decisions for the owner. Follow the [publishing checklist](docs/publishing-checklist.md). No redistribution licence has been granted by this repository; do not assume it is open source.
