---
title: "Radio"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "1678:105591"
figma_node_type: "COMPONENT_SET"
figma_page_id: "0:10803"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# Radio

## Overview

Original Figma name: `Radio`. Published node type: `COMPONENT_SET`. Source page: `🧩  Components` ([0:10803](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `icons/solid/ic-radio-on` | [1678:105630](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-105630) | `icon container` | `icons/solid/ic-radio-on` | `true` | `{"mainComponent": "↳ checked icon#1676:56"}` | `["State=Hovered, Checked=True", "State=Disabled, Checked=True", "State=Enabled, Checked=True"]` |
| `icons/solid/ic-radio-off` | [1678:105792](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-105792) | `icon container` | `icons/solid/ic-radio-off` | `true` | `{"mainComponent": "↳ icon#1676:37"}` | `["State=Hovered, Checked=False", "State=Disabled, Checked=False", "State=Enabled, Checked=False"]` |

Source text samples (not recommended copy):

| Layer | Sample node | Text | Parent path | References | Owning variants |
| --- | --- | --- | --- | --- | --- |
| `label` | [1678:105633](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-105633) | `Checked` | `root` | `{"visible": "👁️ Label#1676:0"}` | `["State=Hovered, Checked=True", "State=Enabled, Checked=True"]` |
| `label` | [1678:105685](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-105685) | `Disabled` | `root` | `{"visible": "👁️ Label#1676:0"}` | `["State=Disabled, Checked=True", "State=Disabled, Checked=False"]` |
| `label` | [1678:105795](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-105795) | `Hovered` | `root` | `{"visible": "👁️ Label#1676:0"}` | `["State=Hovered, Checked=False"]` |
| `label` | [1678:105946](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-105946) | `UnChecked` | `root` | `{"visible": "👁️ Label#1676:0"}` | `["State=Enabled, Checked=False"]` |


## Variants

| Property | Published options | Published default |
| --- | --- | --- |
| `State` | `["Enabled", "Hovered", "Disabled"]` | `Enabled` |
| `Checked` | `["False", "True"]` | `False` |

6 member nodes directly observed in metadata. This is not a Cartesian-product estimate. Names and actual dimensions are preserved:

| Original member name | Node | Width | Height |
| --- | --- | --- | --- |
| `State=Hovered, Checked=True` | [1678:105628](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-105628) | `93` | `40` |
| `State=Disabled, Checked=True` | [1678:105681](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-105681) | `94` | `40` |
| `State=Hovered, Checked=False` | [1678:105790](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-105790) | `93` | `40` |
| `State=Disabled, Checked=False` | [1678:105802](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-105802) | `94` | `40` |
| `State=Enabled, Checked=True` | [1678:105842](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-105842) | `93` | `40` |
| `State=Enabled, Checked=False` | [1678:105942](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-105942) | `111` | `40` |


## Properties

| Original property name | Figma type | Source key | Default | Additional source metadata |
| --- | --- | --- | --- | --- |
| `👁️ Label` | `BOOLEAN` | `👁️ Label#1676:0` | `true` | `{}` |
| `↳ icon` | `INSTANCE_SWAP` | `↳ icon#1676:37` | `0:8092` | `{}` |
| `↳ checked icon` | `INSTANCE_SWAP` | `↳ checked icon#1676:56` | `0:8085` | `{}` |
| `State` | `VARIANT` | `State` | `Enabled` | `{"variantOptions": ["Enabled", "Hovered", "Disabled"]}` |
| `Checked` | `VARIANT` | `Checked` | `False` | `{"variantOptions": ["False", "True"]}` |

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

| Source property | Type | Options | Default |
| --- | --- | --- | --- |
| `State` | `VARIANT` | `["Enabled", "Hovered", "Disabled"]` | `Enabled` |
| `Checked` | `VARIANT` | `["False", "True"]` | `False` |

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `608` × `189` Figma canvas units.

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

Component: [Radio](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1678-105591) — node `1678:105591`.

Page: [🧩  Components](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803) — node `0:10803`.

Published asset key: `9490906bd67f8f4fca2687ca91a279edb6706006`.

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
