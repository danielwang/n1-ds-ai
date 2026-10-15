# Bundled snapshot and approval status

Snapshot date: 15 October 2026. All references needed for the bundled workflows are inside this skill. Start with [design.md](system/design.md); consult the large catalog and raw evidence only when needed.

The snapshot contains 492 published component documents (112 sets and 380 standalone components), 804 observed variant members, and metadata from 12 readable source pages. Deep inspection is partial: 33 detailed design samples, 36 successful node-scoped variable responses (some empty), and six entries with retrieved source-authored description/documentation links. A Figma tool-call limit stopped additional inspection. See [coverage](system/audit/component-documentation-coverage.md).

The shared [token snapshot](system/tokens/README.md) exposes 45 colour values, two raw typography definitions, one raw radius value, and metadata-only discoveries. An empty top-level token group is not proof that N1 lacks those tokens. Some later component-scoped observations have broader coverage; reconcile their context before use.

The authored [Design for Real Work principle](system/foundations/design-principles.md) is preserved verbatim. No complete approval register, approved voice-and-tone policy, measurable accessibility target, comprehensive interaction rules, responsive specification, full mode/alias export, or verified project component API was supplied. Published or extracted does not mean approved. Preserve these distinctions when users request an “approved” N1 interface; use source-backed choices and disclose approval gaps rather than inventing approval.

`system/` preserves the source documentation's relative directory structure and provenance links. The [snapshot manifest](snapshot-manifest.json) records each copied file and its original and packaged SHA-256 hashes. Only repository regeneration instructions are adapted for distribution; guideline text and source data remain unchanged. Original repository scripts and personal environment setup are not runtime dependencies. External documentation links are optional, separately importable sources whose contents have not been bundled as N1 rules.

The installed skill is independent of the original repository and does not require Figma for offline use. Python helpers use Python 3.9+ and its standard library; agents without script execution can read the Markdown index and JSON directly. `agents/openai.yaml` provides OpenAI client metadata; it does not prove installation or execution compatibility in every host.

Run `python3 scripts/validate_package.py` from the skill root to verify bundled references, hashes, catalog identities, and JSON. Use `scripts/find_component.py` for targeted discovery. Skill/package validation does not establish UI correctness, accessibility compliance, or approval of the source guidance.
