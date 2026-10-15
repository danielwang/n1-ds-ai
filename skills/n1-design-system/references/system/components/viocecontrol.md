---
title: "VioceControl"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "7247:14250"
figma_node_type: "COMPONENT"
figma_page_id: "0:10803"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# VioceControl

## Overview

Original Figma name: `VioceControl`. Published node type: `COMPONENT`. Source page: `🧩  Components` ([0:10803](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `Control/Voice` | [7226:14056](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7226-14056) | `root` | [Control/Voice](control-voice.md) | `true` | `{}` | `[]` |
| `icons/agent/mic` | [I7226:14056;7226:7906](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7226-14056;7226-7906) | `Control/Voice` | [icons/agent/mic](icons-agent-mic.md) | `true` | `{}` | `[]` |
| `Microphone` | [I7226:14056;7226:7906;1119:92228](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7226-14056;7226-7906;1119-92228) | `Control/Voice / icons/agent/mic` | `Microphone` | `true` | `{}` | `[]` |
| `icons/generic/Volume` | [I7226:14049;7227:54413](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7226-14049;7227-54413) | `Control/Voice` | [icons/generic/Volume](icons-generic-volume.md) | `true` | `{}` | `[]` |
| `icons/generic/Tuning` | [7226:14048](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7226-14048) | `settings` | [icons/generic/Tuning](icons-generic-tuning.md) | `true` | `{}` | `[]` |

Dependency identities from the published graph:

| Original name | External | Source node ID | Asset key |
| --- | --- | --- | --- |
| `Control/Voice` | `false` | `7226:7903` | `caa0c4b7cb48a9bcefe2849bced980746fa3c28e` |
| `icons/generic/Tuning` | `false` | `7226:9071` | `17eccb8798af10c6518ab0dbf5715d4c1a0040a4` |


## Variants

No variant properties returned for this published node. Further variation: **Needs design review**.


## Properties

No published component properties were returned.

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

**Needs design review** — no explicit state property was returned. State-like text in the component name is a source label only.

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `112` × `36` Figma canvas units.

Explicit responsive configuration was not exposed in the published property list: **Needs design review**.

Raw auto-layout mode, sizing/constraint flags, reflow rules, breakpoints, and interactions: **Needs design review**. Metadata coordinates alone do not establish these rules.

## Accessibility

**Needs design review** — no component-specific accessibility specification or compliance test was verified. Semantic roles, accessible names, focus order, keyboard support, contrast, target size, and assistive-technology behavior require explicit evidence. Visual state names and screenshots do not establish compliance.

## Design tokens

**Needs design review** — no component-scoped variable-definition response has been collected for this node.

See the [shared token snapshot](../tokens/README.md). Mode IDs, alias targets, and individual property-to-variable bindings were not verified here. Equal observed values do not prove alias relationships.

## Figma reference

File key: `01imXcjljmBfqXhqFmv4kz`.

Component: [VioceControl](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7247-14250) — node `7247:14250`.

Page: [🧩  Components](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803) — node `0:10803`.

Published asset key: `69846ff10b115402ef1b88b29688c8cff4a482e8`.

Observation date: 15 October 2026 (Australia/Melbourne).

Evidence: [get_metadata-0-10803.json](../sources/figma/component-evidence/get_metadata-0-10803.json) — `get_metadata`, observed `2026-10-15T03:32:58.572066+00:00`.

Evidence: [list_file_components_for_code_connect-file.json](../sources/figma/component-evidence/list_file_components_for_code_connect-file.json) — `list_file_components_for_code_connect`, observed `2026-10-15T03:32:20.521071+00:00`.

## Implementation reference

**Needs design review** — component-level Code Connect mapping has not been queried for this entry. Page-level empty responses do not establish the absence of a component mapping.

MCP-generated React/Tailwind examples are not a verified project implementation or public component API. No generated runtime API has been imported into this documentation.

## Known gaps

- **Needs design review**: authored purpose/usage rules not retrieved beyond the explicitly cited source descriptions.
- **Needs design review**: raw auto-layout flags, constraints, and responsive behavior.
- **Needs design review**: interaction transitions and accessibility specifications.
- **Needs design review**: complete token bindings, mode-specific values, and alias graph.
- **Needs design review**: implementation API unless independently verified through source code.

Coverage: published identity, properties, nested-instance/text samples, and available metadata geometry. Variant names/dimensions are observed, not synthesized. Unpublished components, external dependency internals, and opaque instance/vector contents are not fully enumerated by the published graph.
