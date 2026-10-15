---
title: "Textarea"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "1921:127924"
figma_node_type: "COMPONENT_SET"
figma_page_id: "0:10803"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# Textarea

## Overview

Original Figma name: `Textarea`. Published node type: `COMPONENT_SET`. Source page: `🧩  Components` ([0:10803](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `✳️ helper text` | [1921:127939](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-127939) | `root` | [FormHelperText](formhelpertext.md) | `false` | `{"visible": "👁️ Help Text#1670:1218"}` | `["Variant=Outlined, State=Enabled, 👁️ Value=False", "Variant=Outlined, State=Enabled, 👁️ Value=True", "Variant=Outlined, State=Hovered, 👁️ Value=False", "Variant=Outlined, State=Hovered, 👁️ Value=True", "Variant=Outlined, State=Focused, 👁️ Value=False", "Variant=Outlined, State=Focused, 👁️ Value=True", "Variant=Outlined, State=Error, 👁️ Value=False", "Variant=Outlined, State=Error, 👁️ Value=True"]` |
| `icons/generic/info` | [I1921:127939;1670:166664](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1921-127939;1670-166664) | `✳️ helper text` | [icons/generic/info](icons-generic-info.md) | `true` | `{"visible": "👁️ Icon#1670:1493"}` | `["Variant=Outlined, State=Enabled, 👁️ Value=False", "Variant=Outlined, State=Enabled, 👁️ Value=True"]` |
| `icons/line/info` | [I1921:127939;1670:166664;960:116546](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1921-127939;1670-166664;960-116546) | `✳️ helper text / icons/generic/info` | `Info Circle` | `true` | `{}` | `["Variant=Outlined, State=Enabled, 👁️ Value=False", "Variant=Outlined, State=Enabled, 👁️ Value=True"]` |
| `scroll` | [2871:214218](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=2871-214218) | `root` | [Scroll](scroll.md) | `false` | `{"visible": "👁️ Scroll#1781:0"}` | `["Variant=Outlined, State=Enabled, 👁️ Value=False", "Variant=Outlined, State=Enabled, 👁️ Value=True", "Variant=Outlined, State=Hovered, 👁️ Value=False", "Variant=Outlined, State=Hovered, 👁️ Value=True", "Variant=Outlined, State=Focused, 👁️ Value=False", "Variant=Outlined, State=Focused, 👁️ Value=True", "Variant=Outlined, State=Error, 👁️ Value=False", "Variant=Outlined, State=Error, 👁️ Value=True", "Variant=Outlined, State=Disabled, 👁️ Value=False", "Variant=Outlined, State=Disabled, 👁️ Value=True"]` |
| `icons/generic/error` | [I1921:128066;1670:166760](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1921-128066;1670-166760) | `✳️ helper text` | [icons/generic/error](icons-generic-error.md) | `true` | `{"visible": "👁️ Icon#1670:1493"}` | `["Variant=Outlined, State=Error, 👁️ Value=False"]` |
| `Danger` | [I1921:128066;1670:166760;1010:42711](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1921-128066;1670-166760;1010-42711) | `✳️ helper text / icons/generic/error` | `Danger` | `true` | `{}` | `["Variant=Outlined, State=Error, 👁️ Value=False"]` |
| `✳️ helper text` | [1921:128105](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-128105) | `root` | `FormHelperText/Disabled` | `false` | `{"visible": "👁️ Help Text#1670:1218"}` | `["Variant=Outlined, State=Disabled, 👁️ Value=False", "Variant=Outlined, State=Disabled, 👁️ Value=True"]` |

Source text samples (not recommended copy):

| Layer | Sample node | Text | Parent path | References | Owning variants |
| --- | --- | --- | --- | --- | --- |
| `value` | [1921:127936](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-127936) | `Label` | `wrap` | `{"visible": "👁️ Label#1707:64"}` | `["Variant=Outlined, State=Enabled, 👁️ Value=False", "Variant=Outlined, State=Hovered, 👁️ Value=False", "Variant=Outlined, State=Error, 👁️ Value=False", "Variant=Outlined, State=Disabled, 👁️ Value=False"]` |
| `helper text` | [I1921:127939;0:14453](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1921-127939;0-14453) | `Caption text, description, notification` | `✳️ helper text` | `{}` | `["Variant=Outlined, State=Enabled, 👁️ Value=False", "Variant=Outlined, State=Enabled, 👁️ Value=True", "Variant=Outlined, State=Error, 👁️ Value=False"]` |
| `0/300` | [6371:9870](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6371-9870) | `0/300` | `root` | `{"visible": "Word Count#6371:0"}` | `["Variant=Outlined, State=Enabled, 👁️ Value=False", "Variant=Outlined, State=Hovered, 👁️ Value=False"]` |
| `value` | [1921:127952](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-127952) | `Value` | `wrap` | `{}` | `["Variant=Outlined, State=Enabled, 👁️ Value=True"]` |
| `label` | [1921:127955](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-127955) | `Label` | `wrap / label focus` | `{}` | `["Variant=Outlined, State=Enabled, 👁️ Value=True", "Variant=Outlined, State=Hovered, 👁️ Value=True", "Variant=Outlined, State=Focused, 👁️ Value=False", "Variant=Outlined, State=Focused, 👁️ Value=True", "Variant=Outlined, State=Error, 👁️ Value=True", "Variant=Outlined, State=Disabled, 👁️ Value=True"]` |
| `0/300` | [6371:9558](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6371-9558) | `0/300` | `wrap` | `{"visible": "Word Count#6371:0"}` | `["Variant=Outlined, State=Enabled, 👁️ Value=True"]` |
| `value` | [1921:127991](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-127991) | `Value (Hovered)` | `wrap` | `{}` | `["Variant=Outlined, State=Hovered, 👁️ Value=True"]` |
| `value` | [1921:128018](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-128018) | `&#124;` | `wrap` | `{}` | `["Variant=Outlined, State=Focused, 👁️ Value=False"]` |
| `value` | [1921:128039](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-128039) | `Value (Focused) &#124;` | `wrap` | `{}` | `["Variant=Outlined, State=Focused, 👁️ Value=True"]` |
| `value` | [1921:128079](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-128079) | `Value (Incorrect)` | `wrap` | `{}` | `["Variant=Outlined, State=Error, 👁️ Value=True"]` |
| `value` | [1921:128118](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-128118) | `Value (Disabled)` | `wrap` | `{}` | `["Variant=Outlined, State=Disabled, 👁️ Value=True"]` |

Dependency identities from the published graph:

| Original name | External | Source node ID | Asset key |
| --- | --- | --- | --- |
| `FormHelperText` | `false` | `199:734` | `93b74c60ec827bfae98958e4dcb1aef4a485cf74` |
| `Scroll` | `false` | `882:180516` | `6acb345c99492748f5e4538442f96c8bedf245e3` |
| `FormHelperText/Disabled` | `true` | `Not exposed` | `e5e10acb1ac8846186ccf61eb140d1b7e26888f0` |


## Variants

| Property | Published options | Published default |
| --- | --- | --- |
| `Variant` | `["Outlined"]` | `Outlined` |
| `State` | `["Enabled", "Hovered", "Focused", "Disabled", "Error"]` | `Enabled` |
| `👁️ Value` | `["False", "True"]` | `False` |

10 member nodes directly observed in metadata. This is not a Cartesian-product estimate. Names and actual dimensions are preserved:

| Original member name | Node | Width | Height |
| --- | --- | --- | --- |
| `Variant=Outlined, State=Enabled, 👁️ Value=False` | [1921:127933](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-127933) | `320` | `98` |
| `Variant=Outlined, State=Enabled, 👁️ Value=True` | [1921:127949](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-127949) | `320` | `98` |
| `Variant=Outlined, State=Hovered, 👁️ Value=False` | [1921:127972](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-127972) | `320` | `98` |
| `Variant=Outlined, State=Hovered, 👁️ Value=True` | [1921:127988](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-127988) | `320` | `98` |
| `Variant=Outlined, State=Focused, 👁️ Value=False` | [1921:128011](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-128011) | `320` | `98` |
| `Variant=Outlined, State=Focused, 👁️ Value=True` | [1921:128035](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-128035) | `320` | `98` |
| `Variant=Outlined, State=Error, 👁️ Value=False` | [1921:128060](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-128060) | `320` | `98` |
| `Variant=Outlined, State=Error, 👁️ Value=True` | [1921:128076](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-128076) | `320` | `98` |
| `Variant=Outlined, State=Disabled, 👁️ Value=False` | [1921:128099](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-128099) | `320` | `98` |
| `Variant=Outlined, State=Disabled, 👁️ Value=True` | [1921:128115](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-128115) | `320` | `98` |


## Properties

| Original property name | Figma type | Source key | Default | Additional source metadata |
| --- | --- | --- | --- | --- |
| `👁️ Help Text` | `BOOLEAN` | `👁️ Help Text#1670:1218` | `false` | `{}` |
| `👁️ Label` | `BOOLEAN` | `👁️ Label#1707:64` | `true` | `{}` |
| `👁️ Scroll` | `BOOLEAN` | `👁️ Scroll#1781:0` | `false` | `{}` |
| `Word Count` | `BOOLEAN` | `Word Count#6371:0` | `false` | `{}` |
| `Variant` | `VARIANT` | `Variant` | `Outlined` | `{"variantOptions": ["Outlined"]}` |
| `State` | `VARIANT` | `State` | `Enabled` | `{"variantOptions": ["Enabled", "Hovered", "Focused", "Disabled", "Error"]}` |
| `👁️ Value` | `VARIANT` | `👁️ Value` | `False` | `{"variantOptions": ["False", "True"]}` |

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

| Source property | Type | Options | Default |
| --- | --- | --- | --- |
| `State` | `VARIANT` | `["Enabled", "Hovered", "Focused", "Disabled", "Error"]` | `Enabled` |

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `1704` × `292` Figma canvas units.

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

Component: [Textarea](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1921-127924) — node `1921:127924`.

Page: [🧩  Components](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803) — node `0:10803`.

Published asset key: `84bc7a0edb04f6d2db2e79d27eada6d810bd8d6d`.

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
