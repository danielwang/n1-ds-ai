---
title: "RadioSelector"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "6904:9418"
figma_node_type: "COMPONENT_SET"
figma_page_id: "0:10803"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# RadioSelector

## Overview

Original Figma name: `RadioSelector`. Published node type: `COMPONENT_SET`. Source page: `🧩  Components` ([0:10803](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `Radio` | [6904:8907](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6904-8907) | `head` | [Radio](radio.md) | `true` | `{}` | `["State=Default", "State=Selected", "State=Hover"]` |
| `icons/solid/ic-radio-off` | [I6904:8907;1678:105944](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I6904-8907;1678-105944) | `head / Radio / icon container` | `icons/solid/ic-radio-off` | `true` | `{"mainComponent": "↳ icon#1676:37"}` | `["State=Default", "State=Hover"]` |
| `icons/solid/ic-radio-on` | [I6904:9421;1678:105844](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I6904-9421;1678-105844) | `head / Radio / icon container` | `icons/solid/ic-radio-on` | `true` | `{"mainComponent": "↳ checked icon#1676:56"}` | `["State=Selected"]` |

Source text samples (not recommended copy):

| Layer | Sample node | Text | Parent path | References | Owning variants |
| --- | --- | --- | --- | --- | --- |
| `label` | [I6904:8907;1678:105946](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I6904-8907;1678-105946) | `UnChecked` | `head / Radio` | `{"visible": "👁️ Label#1676:0"}` | `["State=Default", "State=Hover"]` |
| `label` | [I6904:9421;1678:105846](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I6904-9421;1678-105846) | `Checked` | `head / Radio` | `{"visible": "👁️ Label#1676:0"}` | `["State=Selected"]` |

Dependency identities from the published graph:

| Original name | External | Source node ID | Asset key |
| --- | --- | --- | --- |
| `Radio` | `false` | `1678:105591` | `9490906bd67f8f4fca2687ca91a279edb6706006` |


## Variants

| Property | Published options | Published default |
| --- | --- | --- |
| `State` | `["Default", "Selected", "Hover"]` | `Default` |

3 member nodes directly observed in metadata. This is not a Cartesian-product estimate. Names and actual dimensions are preserved:

| Original member name | Node | Width | Height |
| --- | --- | --- | --- |
| `State=Default` | [6904:9295](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6904-9295) | `449` | `72` |
| `State=Selected` | [6904:9419](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6904-9419) | `449` | `72` |
| `State=Hover` | [6907:6533](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6907-6533) | `449` | `72` |


## Properties

| Original property name | Figma type | Source key | Default | Additional source metadata |
| --- | --- | --- | --- | --- |
| `State` | `VARIANT` | `State` | `Default` | `{"variantOptions": ["Default", "Selected", "Hover"]}` |

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

| Source property | Type | Options | Default |
| --- | --- | --- | --- |
| `State` | `VARIANT` | `["Default", "Selected", "Hover"]` | `Default` |

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `489` × `296` Figma canvas units.

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

Component: [RadioSelector](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6904-9418) — node `6904:9418`.

Page: [🧩  Components](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803) — node `0:10803`.

Published asset key: `631eebf03ffda7a490f0984a4152609797394733`.

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
