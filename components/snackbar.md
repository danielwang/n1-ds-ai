---
title: "Snackbar"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "82:159"
figma_node_type: "COMPONENT_SET"
figma_page_id: "0:10803"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# Snackbar

## Overview

Original Figma name: `Snackbar`. Published node type: `COMPONENT_SET`. Source page: `🧩  Components` ([0:10803](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `icons/color/info` | [82:905](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=82-905) | `icon` | [icons/color/info](icons-color-info.md) | `true` | `{}` | `["Severity=Info"]` |
| `✳️ primary action` | [1799:133244](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1799-133244) | `actions` | [Link](link.md) | `true` | `{"visible": "👁️ Primary Action#1678:216"}` | `["Severity=Info", "Severity=Success", "Severity=Warning", "Severity=Error"]` |
| `✳️ secondary action` | [1799:133412](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1799-133412) | `actions` | [Button](button.md) | `false` | `{"visible": "👁️ Secondary Action#2879:93"}` | `["Severity=Info", "Severity=Success", "Severity=Warning", "Severity=Error"]` |
| `↳ close` | [1678:111913](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-111913) | `close` | [Button/Icon](button-icon.md) | `true` | `{}` | `["Severity=Info", "Severity=Success", "Severity=Warning", "Severity=Error"]` |
| `icons/placeholder` | [I1678:111913;1670:116827](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1678-111913;1670-116827) | `close / ↳ close` | [icons/generic/close](icons-generic-close.md) | `true` | `{"mainComponent": "↳ icon#1670:1363"}` | `["Severity=Info", "Severity=Success", "Severity=Warning", "Severity=Error"]` |
| `icons/color/Check Circle` | [82:1004](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=82-1004) | `icon` | [icons/color/Check Circle](icons-color-check-circle.md) | `true` | `{}` | `["Severity=Success"]` |
| `icons/color/warning` | [82:1089](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=82-1089) | `icon` | [icons/color/warning](icons-color-warning.md) | `true` | `{}` | `["Severity=Warning"]` |
| `icons/color/error` | [82:1181](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=82-1181) | `icon` | [icons/color/error](icons-color-error.md) | `true` | `{}` | `["Severity=Error"]` |

Source text samples (not recommended copy):

| Layer | Sample node | Text | Parent path | References | Owning variants |
| --- | --- | --- | --- | --- | --- |
| `description` | [0:15197](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-15197) | `This is a info message!` | `root` | `{}` | `["Severity=Info"]` |
| `text` | [I1799:133244;209:235819](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1799-133244;209-235819) | `Action` | `actions / ✳️ primary action` | `{}` | `["Severity=Info", "Severity=Success", "Severity=Warning", "Severity=Error"]` |
| `description` | [0:15191](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-15191) | `This is a success message!` | `root` | `{}` | `["Severity=Success"]` |
| `description` | [0:15176](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-15176) | `This is a warning message!` | `root` | `{}` | `["Severity=Warning"]` |
| `description` | [0:15161](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-15161) | `This is a error message!` | `root` | `{}` | `["Severity=Error"]` |

Dependency identities from the published graph:

| Original name | External | Source node ID | Asset key |
| --- | --- | --- | --- |
| `icons/color/info` | `false` | `5385:11333` | `cbe8f0bd4b172218e3733864aecc98880f59c2b7` |
| `Link` | `false` | `213:239018` | `9cedc5f1587066f09b6ffb446399ade5389ea1d8` |
| `Button` | `false` | `1667:129167` | `8bad54a5afd20d7ad0b1e146f234c7cd40728dd5` |
| `Button/Icon` | `false` | `11:812` | `8b228433cfac383928ea1c87230d866aefa90ef0` |
| `icons/color/Check Circle` | `false` | `5385:11332` | `340fda96530122e59e9413dd679a3ebee6fbf2d0` |
| `icons/color/warning` | `false` | `5385:11335` | `0f6c0eb73bfb8c9adeae832f92f3accc62ea2c9e` |
| `icons/color/error` | `false` | `5385:11334` | `f6401a542be0ec4e639f610e271b4523907fd98e` |


## Variants

| Property | Published options | Published default |
| --- | --- | --- |
| `Severity` | `["Info", "Error", "Warning", "Success"]` | `Info` |

4 member nodes directly observed in metadata. This is not a Cartesian-product estimate. Names and actual dimensions are preserved:

| Original member name | Node | Width | Height |
| --- | --- | --- | --- |
| `Severity=Info` | [0:15192](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-15192) | `420` | `56` |
| `Severity=Success` | [0:15177](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-15177) | `420` | `56` |
| `Severity=Warning` | [0:15162](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-15162) | `420` | `56` |
| `Severity=Error` | [0:15147](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-15147) | `420` | `56` |


## Properties

| Original property name | Figma type | Source key | Default | Additional source metadata |
| --- | --- | --- | --- | --- |
| `👁️ Close` | `BOOLEAN` | `👁️ Close#1678:210` | `true` | `{}` |
| `👁️ Primary Action` | `BOOLEAN` | `👁️ Primary Action#1678:216` | `true` | `{}` |
| `👁️ Secondary Action` | `BOOLEAN` | `👁️ Secondary Action#2879:93` | `false` | `{}` |
| `Severity` | `VARIANT` | `Severity` | `Info` | `{"variantOptions": ["Info", "Error", "Warning", "Success"]}` |

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

| Source property | Type | Options | Default |
| --- | --- | --- | --- |
| `Severity` | `VARIANT` | `["Info", "Error", "Warning", "Success"]` | `Info` |

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `500` × `376` Figma canvas units.

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

Component: [Snackbar](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=82-159) — node `82:159`.

Page: [🧩  Components](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803) — node `0:10803`.

Published asset key: `f0ae3c750d2cbc1a35796b81b319ad88770e7a4a`.

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
