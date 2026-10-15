---
title: "TablePagination"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "1612:129994"
figma_node_type: "COMPONENT_SET"
figma_page_id: "0:10803"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# TablePagination

## Overview

Original Figma name: `TablePagination`. Published node type: `COMPONENT_SET`. Source page: `🧩  Components` ([0:10803](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `Switch` | [1739:142109](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1739-142109) | `root` | [Switch](switch.md) | `true` | `{"visible": "Dense#1739:15"}` | `["Variant=Pagination, On Mobile=False", "Variant=Pagination, On Mobile=True"]` |
| `icons/solid/ic-eva:arrow-ios-downward-fill` | [1612:130026](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130026) | `select` | `icons/solid/ic-eva:arrow-ios-downward-fill` | `true` | `{}` | `["Variant=Pagination, On Mobile=False"]` |
| `Button/Icon` | [1612:130029](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130029) | `next/prev` | `IconButton/Default/S/Disabled` | `true` | `{}` | `["Variant=Pagination, On Mobile=False"]` |
| `icons/placeholder` | [I1612:130029;1670:145447](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1612-130029;1670-145447) | `next/prev / Button/Icon` | `icons/solid/ic-eva:arrow-ios-back-fill` | `true` | `{"mainComponent": "↳ icon#1670:1397"}` | `["Variant=Pagination, On Mobile=False"]` |
| `Button/Icon` | [1612:130030](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130030) | `next/prev` | `IconButton/Inherit/S/Enabled` | `true` | `{}` | `["Variant=Pagination, On Mobile=False"]` |
| `icons/placeholder` | [I1612:130030;1670:139839](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1612-130030;1670-139839) | `next/prev / Button/Icon` | `icons/solid/ic-eva:arrow-ios-forward-fill` | `true` | `{"mainComponent": "↳ icon#1670:1382"}` | `["Variant=Pagination, On Mobile=False"]` |
| `icons/solid/ic-eva:arrow-ios-downward-fill` | [1739:144702](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1739-144702) | `stack / select` | `icons/solid/ic-eva:arrow-ios-downward-fill` | `true` | `{}` | `["Variant=Pagination, On Mobile=True"]` |
| `Button/Icon` | [1739:144705](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1739-144705) | `stack / next/prev` | `IconButton/Default/S/Disabled` | `true` | `{}` | `["Variant=Pagination, On Mobile=True"]` |
| `icons/placeholder` | [I1739:144705;1670:145447](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1739-144705;1670-145447) | `stack / next/prev / Button/Icon` | `icons/solid/ic-eva:arrow-ios-back-fill` | `true` | `{"mainComponent": "↳ icon#1670:1397"}` | `["Variant=Pagination, On Mobile=True"]` |
| `Button/Icon` | [1739:144706](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1739-144706) | `stack / next/prev` | `IconButton/Inherit/S/Enabled` | `true` | `{}` | `["Variant=Pagination, On Mobile=True"]` |
| `icons/placeholder` | [I1739:144706;1670:139839](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1739-144706;1670-139839) | `stack / next/prev / Button/Icon` | `icons/solid/ic-eva:arrow-ios-forward-fill` | `true` | `{"mainComponent": "↳ icon#1670:1382"}` | `["Variant=Pagination, On Mobile=True"]` |

Source text samples (not recommended copy):

| Layer | Sample node | Text | Parent path | References | Owning variants |
| --- | --- | --- | --- | --- | --- |
| `label` | [I1739:142109;1676:109789](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1739-142109;1676-109789) | `UnChecked` | `Switch` | `{"visible": "👁️ Start Label#1676:94"}` | `["Variant=Pagination, On Mobile=False", "Variant=Pagination, On Mobile=True"]` |
| `label` | [I1739:142109;1676:109792](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1739-142109;1676-109792) | `Dense` | `Switch` | `{"visible": "👁️ End Label#1676:139"}` | `["Variant=Pagination, On Mobile=False", "Variant=Pagination, On Mobile=True"]` |
| `Rows per page:` | [1612:130023](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130023) | `Rows per page:` | `root` | `{}` | `["Variant=Pagination, On Mobile=False"]` |
| `5` | [1612:130025](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130025) | `5` | `select` | `{}` | `["Variant=Pagination, On Mobile=False"]` |
| `6-10 of 11` | [1612:130027](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130027) | `6-10 of 11` | `root` | `{}` | `["Variant=Pagination, On Mobile=False"]` |
| `Rows per page:` | [1739:144699](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1739-144699) | `Rows per page:` | `stack` | `{}` | `["Variant=Pagination, On Mobile=True"]` |
| `5` | [1739:144701](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1739-144701) | `5` | `stack / select` | `{}` | `["Variant=Pagination, On Mobile=True"]` |
| `6-10 of 11` | [1739:144703](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1739-144703) | `6-10 of 11` | `stack` | `{}` | `["Variant=Pagination, On Mobile=True"]` |

Dependency identities from the published graph:

| Original name | External | Source node ID | Asset key |
| --- | --- | --- | --- |
| `Switch` | `false` | `64:63214` | `8a50d50bc5f44abf5f08d576a6e69a7b83a00ade` |
| `icons/solid/ic-eva:arrow-ios-downward-fill` | `true` | `Not exposed` | `6dd4acddd97b0183d3f274a0db881dbcfb668052` |
| `IconButton/Default/S/Disabled` | `true` | `Not exposed` | `5c3e829cb0c34f8cf257831d1424e72fd01ecf88` |
| `IconButton/Inherit/S/Enabled` | `true` | `Not exposed` | `5f07934466a6c3aee2e8547d17c80336e33fcbf4` |


## Variants

| Property | Published options | Published default |
| --- | --- | --- |
| `Variant` | `["Pagination"]` | `Pagination` |
| `On Mobile` | `["False", "True"]` | `False` |

2 member nodes directly observed in metadata. This is not a Cartesian-product estimate. Names and actual dimensions are preserved:

| Original member name | Node | Width | Height |
| --- | --- | --- | --- |
| `Variant=Pagination, On Mobile=False` | [1612:130022](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130022) | `1080` | `58` |
| `Variant=Pagination, On Mobile=True` | [1739:144697](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1739-144697) | `375` | `118` |


## Properties

| Original property name | Figma type | Source key | Default | Additional source metadata |
| --- | --- | --- | --- | --- |
| `Dense` | `BOOLEAN` | `Dense#1739:15` | `true` | `{}` |
| `Variant` | `VARIANT` | `Variant` | `Pagination` | `{"variantOptions": ["Pagination"]}` |
| `On Mobile` | `VARIANT` | `On Mobile` | `False` | `{"variantOptions": ["False", "True"]}` |

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

**Needs design review** — no explicit state property was returned. State-like text in the component name is a source label only.

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `1160` × `296` Figma canvas units.

These are the component-set canvas bounds, not a rendered component size; use member dimensions under Variants.

Source device-labelled properties: `On Mobile` = `["False", "True"]`. These labels do not establish breakpoints.

Raw auto-layout mode, sizing/constraint flags, reflow rules, breakpoints, and interactions: **Needs design review**. Metadata coordinates alone do not establish these rules.

## Accessibility

**Needs design review** — no component-specific accessibility specification or compliance test was verified. Semantic roles, accessible names, focus order, keyboard support, contrast, target size, and assistive-technology behavior require explicit evidence. Visual state names and screenshots do not establish compliance.

## Design tokens

**Needs design review** — no component-scoped variable-definition response has been collected for this node.

See the [shared token snapshot](../tokens/README.md). Mode IDs, alias targets, and individual property-to-variable bindings were not verified here. Equal observed values do not prove alias relationships.

## Figma reference

File key: `01imXcjljmBfqXhqFmv4kz`.

Component: [TablePagination](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-129994) — node `1612:129994`.

Page: [🧩  Components](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803) — node `0:10803`.

Published asset key: `dd5b0f12c6dff9725be3ecca2c77a3390e032710`.

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
