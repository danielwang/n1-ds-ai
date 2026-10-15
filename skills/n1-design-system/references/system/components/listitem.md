---
title: "ListItem"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "1685:106029"
figma_node_type: "COMPONENT_SET"
figma_page_id: "0:10803"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# ListItem

## Overview

Original Figma name: `ListItem`. Published node type: `COMPONENT_SET`. Source page: `🧩  Components` ([0:10803](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `✳️ start icon` | [2539:658543](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=2539-658543) | `root` | [_Icon](icon.md) | `false` | `{"visible": "👁️ Start Icon#1685:27", "mainComponent": "↳ start icon#2539:168"}` | `["State=Enabled", "State=Hovered", "State=Selected", "State=Disabled"]` |
| `icons/placeholder` | [I2539:658543;60:85910](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2539-658543;60-85910) | `✳️ start icon` | [icons/placeholder](icons-placeholder.md) | `true` | `{"mainComponent": "↳ icon#1758:10"}` | `["State=Enabled"]` |
| `✳️ text` | [2539:642526](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=2539-642526) | `root` | [ListItemText](listitemtext.md) | `true` | `{}` | `["State=Enabled", "State=Hovered", "State=Selected", "State=Disabled"]` |
| `✳️ end icon` | [2539:666786](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=2539-666786) | `root` | [_Icon](icon.md) | `false` | `{"visible": "👁️ End Icon#1685:29", "mainComponent": "↳ end icon#2539:173"}` | `["State=Enabled", "State=Hovered", "State=Selected", "State=Disabled"]` |

Source text samples (not recommended copy):

| Layer | Sample node | Text | Parent path | References | Owning variants |
| --- | --- | --- | --- | --- | --- |
| `primary` | [I2539:642526;2539:642520](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2539-642526;2539-642520) | `Primary Text` | `✳️ text` | `{"visible": "👁️ Primary Text#2539:69", "characters": "↳ primary text#2878:0"}` | `["State=Enabled", "State=Hovered", "State=Selected", "State=Disabled"]` |
| `secondary` | [I2539:642526;2539:642521](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2539-642526;2539-642521) | `Secondary text` | `✳️ text` | `{"visible": "👁️ Secondary Text#2539:70", "characters": "↳ secondary text#2878:1"}` | `["State=Enabled", "State=Hovered", "State=Selected", "State=Disabled"]` |

Dependency identities from the published graph:

| Original name | External | Source node ID | Asset key |
| --- | --- | --- | --- |
| `ListItemText` | `false` | `2539:642522` | `90c0f3580b1817364536c34d80279eb5b18e0dee` |


## Variants

| Property | Published options | Published default |
| --- | --- | --- |
| `State` | `["Enabled", "Hovered", "Selected", "Disabled"]` | `Enabled` |

4 member nodes directly observed in metadata. This is not a Cartesian-product estimate. Names and actual dimensions are preserved:

| Original member name | Node | Width | Height |
| --- | --- | --- | --- |
| `State=Enabled` | [231:52678](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=231-52678) | `320` | `38` |
| `State=Hovered` | [1685:106042](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1685-106042) | `320` | `38` |
| `State=Selected` | [1685:106054](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1685-106054) | `320` | `38` |
| `State=Disabled` | [1685:106030](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1685-106030) | `320` | `38` |


## Properties

| Original property name | Figma type | Source key | Default | Additional source metadata |
| --- | --- | --- | --- | --- |
| `👁️ Start Icon` | `BOOLEAN` | `👁️ Start Icon#1685:27` | `false` | `{}` |
| `👁️ End Icon` | `BOOLEAN` | `👁️ End Icon#1685:29` | `false` | `{}` |
| `↳ start icon` | `INSTANCE_SWAP` | `↳ start icon#2539:168` | `60:97057` | `{}` |
| `↳ end icon` | `INSTANCE_SWAP` | `↳ end icon#2539:173` | `60:97057` | `{}` |
| `State` | `VARIANT` | `State` | `Enabled` | `{"variantOptions": ["Enabled", "Hovered", "Selected", "Disabled"]}` |

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

| Source property | Type | Options | Default |
| --- | --- | --- | --- |
| `State` | `VARIANT` | `["Enabled", "Hovered", "Selected", "Disabled"]` | `Enabled` |

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `400` × `304` Figma canvas units.

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

Component: [ListItem](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1685-106029) — node `1685:106029`.

Page: [🧩  Components](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803) — node `0:10803`.

Published asset key: `f57cd0eb4afe5d05a606f45edc583c7c9ba194e5`.

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
