---
title: "Table/Cell"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "3638:58012"
figma_node_type: "COMPONENT_SET"
figma_page_id: "0:10803"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# Table/Cell

## Overview

Original Figma name: `Table/Cell`. Published node type: `COMPONENT_SET`. Source page: `🧩  Components` ([0:10803](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `✳️ checkbox` | [3638:58015](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3638-58015) | `checkbox` | `Checkbox` | `true` | `{}` | `["Variant=Th", "Variant=Td"]` |
| `icons/solid/ic-eva:arrow-downward-fill` | [3638:58018](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3638-58018) | `stack` | `icons/solid/ic-eva:arrow-downward-fill` | `false` | `{"visible": "👁️ Sort Arrow#1682:437"}` | `["Variant=Th"]` |
| `icons/solid/ic-checkbox-on` | [I3638:58021;1676:108566](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I3638-58021;1676-108566) | `checkbox / ✳️ checkbox / icon container` | `icons/solid/ic-checkbox-on` | `true` | `{"mainComponent": "↳ checked icon#1676:56"}` | `["Variant=Td"]` |
| `✳️ primary action` | [3638:58029](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3638-58029) | `root` | `IconButton` | `true` | `{"visible": "👁️ Secondary Action#2556:4", "mainComponent": "↳ secondary action#2556:0"}` | `["Variant=Action"]` |
| `icons/generic/Chevron Right` | [I3638:58029;1670:120827](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I3638-58029;1670-120827) | `✳️ primary action` | [icons/generic/Chevron Right](icons-generic-chevron-right.md) | `true` | `{"mainComponent": "↳ icon#1670:1363"}` | `["Variant=Action"]` |
| `Alt Arrow Right` | [I3638:58029;1670:120827;1225:39047](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I3638-58029;1670-120827;1225-39047) | `✳️ primary action / icons/generic/Chevron Right` | `Alt Arrow Right` | `true` | `{}` | `["Variant=Action"]` |
| `✳️ secondary action` | [3638:58030](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3638-58030) | `root` | `IconButton` | `false` | `{"visible": "👁️ Primary Action#2878:10", "mainComponent": "↳ primary action#1682:447"}` | `["Variant=Action"]` |

Source text samples (not recommended copy):

| Layer | Sample node | Text | Parent path | References | Owning variants |
| --- | --- | --- | --- | --- | --- |
| `th text` | [3638:58017](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3638-58017) | `Table th` | `stack` | `{"visible": "👁️ Primary Text#2587:0"}` | `["Variant=Th"]` |
| `label` | [I3638:58021;1676:108568](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I3638-58021;1676-108568) | `Checked` | `checkbox / ✳️ checkbox` | `{"visible": "👁️ Label#1676:0"}` | `["Variant=Td"]` |
| `primary text` | [3638:58026](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3638-58026) | `Table td` | `stack / text` | `{"visible": "👁️ Primary Text#2587:0"}` | `["Variant=Td"]` |
| `secondary text` | [3638:58027](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3638-58027) | `Table td` | `stack / text` | `{"visible": "👁️ Secondary Text#2541:10"}` | `["Variant=Td"]` |

Dependency identities from the published graph:

| Original name | External | Source node ID | Asset key |
| --- | --- | --- | --- |
| `Checkbox` | `true` | `Not exposed` | `efa770849f98a4872a1e7d6c6389042f32ac9202` |
| `icons/solid/ic-eva:arrow-downward-fill` | `true` | `Not exposed` | `72e0c676b0eb6921f462ff6945bba216e239690b` |


## Variants

| Property | Published options | Published default |
| --- | --- | --- |
| `Variant` | `["Th", "Action", "Td"]` | `Th` |

3 member nodes directly observed in metadata. This is not a Cartesian-product estimate. Names and actual dimensions are preserved:

| Original member name | Node | Width | Height |
| --- | --- | --- | --- |
| `Variant=Th` | [3638:58013](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3638-58013) | `83` | `56` |
| `Variant=Td` | [3638:58019](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3638-58019) | `81` | `56` |
| `Variant=Action` | [3638:58028](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3638-58028) | `68` | `56` |


## Properties

| Original property name | Figma type | Source key | Default | Additional source metadata |
| --- | --- | --- | --- | --- |
| `👁️ Sort Arrow` | `BOOLEAN` | `👁️ Sort Arrow#1682:437` | `false` | `{}` |
| `👁️ Checkbox` | `BOOLEAN` | `👁️ Checkbox#1682:441` | `false` | `{}` |
| `↳ primary action` | `INSTANCE_SWAP` | `↳ primary action#1682:447` | `113:102800` | `{}` |
| `👁️ Secondary Text` | `BOOLEAN` | `👁️ Secondary Text#2541:10` | `false` | `{}` |
| `↳ secondary action` | `INSTANCE_SWAP` | `↳ secondary action#2556:0` | `113:102800` | `{}` |
| `👁️ Secondary Action` | `BOOLEAN` | `👁️ Secondary Action#2556:4` | `true` | `{}` |
| `👁️ Primary Text` | `BOOLEAN` | `👁️ Primary Text#2587:0` | `true` | `{}` |
| `👁️ Primary Action` | `BOOLEAN` | `👁️ Primary Action#2878:10` | `false` | `{}` |
| `Variant` | `VARIANT` | `Variant` | `Th` | `{"variantOptions": ["Th", "Action", "Td"]}` |

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

**Needs design review** — no explicit state property was returned. State-like text in the component name is a source label only.

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `328` × `104` Figma canvas units.

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

Component: [Table/Cell](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3638-58012) — node `3638:58012`.

Page: [🧩  Components](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803) — node `0:10803`.

Published asset key: `68206f275f2cacc415495368a4967df922b1f946`.

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
