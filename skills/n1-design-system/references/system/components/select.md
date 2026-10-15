---
title: "Select"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "5116:29117"
figma_node_type: "COMPONENT_SET"
figma_page_id: "0:10803"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# Select

## Overview

Original Figma name: `Select`. Published node type: `COMPONENT_SET`. Source page: `🧩  Components` ([0:10803](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `TextField` | [3007:30288](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3007-30288) | `root` | [TextField](input.md) | `true` | `{}` | `["Type=Single, Size=LG", "Type=Single, Size=SM", "Type=Multiple, Size=LG", "Type=Multiple, Size=SM"]` |
| `✳️ end adornment` | [I3007:30288;1774:138235](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I3007-30288;1774-138235) | `TextField / wrap / end adornment` | [Button/Icon](button-icon.md) | `false` | `{"visible": "👁️ End Adornment#1670:783", "mainComponent": "↳ end adornment#1670:1073"}` | `["Type=Single, Size=LG", "Type=Single, Size=SM", "Type=Multiple, Size=LG", "Type=Multiple, Size=SM"]` |
| `start adornment` | [I3007:30288;1774:149039](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I3007-30288;1774-149039) | `TextField / wrap / select arrow` | `icons/solid/ic-eva:arrow-ios-downward-fill` | `true` | `{"visible": "👁️ Select Arrow#1774:0"}` | `["Type=Single, Size=LG", "Type=Single, Size=SM", "Type=Multiple, Size=LG", "Type=Multiple, Size=SM"]` |
| `✳️ helper text` | [I3007:30288;1670:171151](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I3007-30288;1670-171151) | `TextField` | [FormHelperText](formhelpertext.md) | `false` | `{"visible": "👁️ Help Text#1670:1218"}` | `["Type=Single, Size=LG", "Type=Single, Size=SM", "Type=Multiple, Size=LG", "Type=Multiple, Size=SM"]` |
| `Chip` | [5116:29754](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5116-29754) | `Frame 14820` | [Chip](chip.md) | `true` | `{}` | `["Type=Multiple, Size=LG", "Type=Multiple, Size=SM"]` |
| `✳️ icon` | [I5116:29754;1680:123820](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5116-29754;1680-123820) | `Frame 14820 / Chip` | [icons/placeholder](icons-placeholder.md) | `false` | `{"visible": "👁️ Icon#1680:360", "mainComponent": "↳ icon#2539:119"}` | `["Type=Multiple, Size=LG", "Type=Multiple, Size=SM"]` |
| `action` | [I5116:29754;1412:131277](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5116-29754;1412-131277) | `Frame 14820 / Chip` | [icons/generic/close-2](icons-generic-close-2.md) | `true` | `{"visible": "👁️ Action#1680:71", "mainComponent": "↳ action icon#1680:1227"}` | `["Type=Multiple, Size=LG", "Type=Multiple, Size=SM"]` |

Source text samples (not recommended copy):

| Layer | Sample node | Text | Parent path | References | Owning variants |
| --- | --- | --- | --- | --- | --- |
| `value` | [I3007:30288;1670:171145](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I3007-30288;1670-171145) | `Value` | `TextField / wrap` | `{}` | `["Type=Single, Size=LG", "Type=Single, Size=SM"]` |
| `label` | [I3007:30288;1670:171150](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I3007-30288;1670-171150) | `Label` | `TextField / wrap / label focus` | `{}` | `["Type=Single, Size=LG", "Type=Single, Size=SM"]` |
| `value` | [I5116:29753;1670:171145](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5116-29753;1670-171145) | ` ` | `TextField / wrap` | `{}` | `["Type=Multiple, Size=LG", "Type=Multiple, Size=SM"]` |
| `label` | [I5116:29753;1670:171150](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5116-29753;1670-171150) | `Open AI` | `TextField / wrap / label focus` | `{}` | `["Type=Multiple, Size=LG", "Type=Multiple, Size=SM"]` |
| `label` | [I5116:29754;1412:131276](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5116-29754;1412-131276) | `gpt-4o` | `Frame 14820 / Chip / label container` | `{}` | `["Type=Multiple, Size=LG", "Type=Multiple, Size=SM"]` |
| `label` | [I5116:29755;1412:131276](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5116-29755;1412-131276) | `gpt-4o mini` | `Frame 14820 / Chip / label container` | `{}` | `["Type=Multiple, Size=LG", "Type=Multiple, Size=SM"]` |

Dependency identities from the published graph:

| Original name | External | Source node ID | Asset key |
| --- | --- | --- | --- |
| `TextField` | `false` | `194:62777` | `da78f476840d89866b3daab25f4da5317f52c132` |
| `Chip` | `false` | `86:5732` | `7c63c229332e9427a24eb9a6e41e835449bc7ed1` |


## Variants

| Property | Published options | Published default |
| --- | --- | --- |
| `Type` | `["Single", "Multiple"]` | `Single` |
| `Size` | `["LG", "SM"]` | `LG` |

4 member nodes directly observed in metadata. This is not a Cartesian-product estimate. Names and actual dimensions are preserved:

| Original member name | Node | Width | Height |
| --- | --- | --- | --- |
| `Type=Single, Size=LG` | [3007:30299](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3007-30299) | `320` | `54` |
| `Type=Single, Size=SM` | [6365:11469](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6365-11469) | `320` | `40` |
| `Type=Multiple, Size=LG` | [5116:29780](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5116-29780) | `450` | `54` |
| `Type=Multiple, Size=SM` | [6365:11441](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6365-11441) | `450` | `54` |


## Properties

| Original property name | Figma type | Source key | Default | Additional source metadata |
| --- | --- | --- | --- | --- |
| `Type` | `VARIANT` | `Type` | `Single` | `{"variantOptions": ["Single", "Multiple"]}` |
| `Size` | `VARIANT` | `Size` | `LG` | `{"variantOptions": ["LG", "SM"]}` |

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

**Needs design review** — no explicit state property was returned. State-like text in the component name is a source label only.

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `519` × `322` Figma canvas units.

These are the component-set canvas bounds, not a rendered component size; use member dimensions under Variants.

Explicit responsive configuration was not exposed in the published property list: **Needs design review**.

Raw auto-layout mode, sizing/constraint flags, reflow rules, breakpoints, and interactions: **Needs design review**. Metadata coordinates alone do not establish these rules.

## Accessibility

**Needs design review** — no component-specific accessibility specification or compliance test was verified. Semantic roles, accessible names, focus order, keyboard support, contrast, target size, and assistive-technology behavior require explicit evidence. Visual state names and screenshots do not establish compliance.

## Design tokens

**Needs design review** — no component-scoped variable-definition response has been collected for this node.

See the [shared token snapshot](../tokens/README.md). Mode IDs, alias targets, and individual property-to-variable bindings were not verified here. Equal observed values do not prove alias relationships.

## Figma reference

File key: `01imXcjljmBfqXhqFmv4kz`.

Component: [Select](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5116-29117) — node `5116:29117`.

Page: [🧩  Components](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803) — node `0:10803`.

Published asset key: `30d853a966f52059c02067e3dc6d3f2b7c683d4d`.

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
