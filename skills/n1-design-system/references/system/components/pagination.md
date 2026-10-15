---
title: "Pagination"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "86:12913"
figma_node_type: "COMPONENT_SET"
figma_page_id: "0:10803"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# Pagination

## Overview

Original Figma name: `Pagination`. Published node type: `COMPONENT_SET`. Source page: `🧩  Components` ([0:10803](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `Button/Icon` | [1612:130111](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130111) | `root` | [Button/Icon](button-icon.md) | `true` | `{}` | `["Size=L", "Size=S"]` |
| `icons/placeholder` | [I1612:130111;1670:120827](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1612-130111;1670-120827) | `Button/Icon` | `icons/solid/ic-eva:arrow-ios-back-fill` | `true` | `{"mainComponent": "↳ icon#1670:1363"}` | `["Size=L", "Size=S"]` |
| `Button/Icon` | [1612:130119](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130119) | `root` | `IconButton/Inherit/S/Enabled` | `true` | `{}` | `["Size=L", "Size=S"]` |
| `icons/placeholder` | [I1612:130119;1670:139839](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1612-130119;1670-139839) | `Button/Icon` | `icons/solid/ic-eva:arrow-ios-forward-fill` | `true` | `{"mainComponent": "↳ icon#1670:1382"}` | `["Size=L", "Size=S"]` |

Source text samples (not recommended copy):

| Layer | Sample node | Text | Parent path | References | Owning variants |
| --- | --- | --- | --- | --- | --- |
| `1` | [1612:130113](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130113) | `1` | `selected` | `{}` | `["Size=L", "Size=S"]` |
| `2` | [1612:130114](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130114) | `2` | `root` | `{}` | `["Size=L", "Size=S"]` |
| `3` | [1612:130115](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130115) | `3` | `root` | `{}` | `["Size=L", "Size=S"]` |
| `4` | [1612:130116](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130116) | `4` | `root` | `{}` | `["Size=L", "Size=S"]` |
| `5` | [1612:130117](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130117) | `5` | `root` | `{}` | `["Size=L", "Size=S"]` |
| `…` | [1612:130118](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130118) | `…` | `root` | `{}` | `["Size=L", "Size=S"]` |

Dependency identities from the published graph:

| Original name | External | Source node ID | Asset key |
| --- | --- | --- | --- |
| `Button/Icon` | `false` | `11:812` | `8b228433cfac383928ea1c87230d866aefa90ef0` |
| `IconButton/Inherit/S/Enabled` | `true` | `Not exposed` | `5f07934466a6c3aee2e8547d17c80336e33fcbf4` |


## Variants

| Property | Published options | Published default |
| --- | --- | --- |
| `Size` | `["L", "S"]` | `L` |

2 member nodes directly observed in metadata. This is not a Cartesian-product estimate. Names and actual dimensions are preserved:

| Original member name | Node | Width | Height |
| --- | --- | --- | --- |
| `Size=L` | [1612:130110](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130110) | `362` | `40` |
| `Size=S` | [1612:130166](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-130166) | `320` | `26` |


## Properties

| Original property name | Figma type | Source key | Default | Additional source metadata |
| --- | --- | --- | --- | --- |
| `Size` | `VARIANT` | `Size` | `L` | `{"variantOptions": ["L", "S"]}` |

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

**Needs design review** — no explicit state property was returned. State-like text in the component name is a source label only.

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `438` × `338` Figma canvas units.

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

Component: [Pagination](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=86-12913) — node `86:12913`.

Page: [🧩  Components](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803) — node `0:10803`.

Published asset key: `d58d4174a097cb5b84ad436ee9693ebfa6097f87`.

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
