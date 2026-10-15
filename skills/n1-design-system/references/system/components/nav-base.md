---
title: "_Nav/base"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "3824:33443"
figma_node_type: "COMPONENT"
figma_page_id: "1621:252918"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# _Nav/base

## Overview

Original Figma name: `_Nav/base`. Published node type: `COMPONENT`. Source page: `🧩 Landmarks` ([1621:252918](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1621-252918)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `Button/Icon` | [3824:33431](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3824-33431) | `openClose` | `IconButton/Error/Xs/Enabled` | `true` | `{}` | `[]` |
| `icons/placeholder` | [I3824:33431;1670:146099](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I3824-33431;1670-146099) | `openClose / Button/Icon` | `icons/solid/ic-eva:arrow-ios-back-fill` | `true` | `{"mainComponent": "↳ icon#1670:1371"}` | `[]` |
| `_Logo/aquauni` | [7327:39580](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7327-39580) | `logo` | [_Logo/aquauni](logo-aquauni.md) | `true` | `{}` | `[]` |
| `UserLogin` | [3824:33439](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3824-33439) | `Frame 14764` | [UserLogin](userlogin.md) | `true` | `{}` | `[]` |
| `icons/avatar/user` | [I3824:33439;6612:34912](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I3824-33439;6612-34912) | `Frame 14764 / UserLogin` | [icons/avatar/user](icons-avatar-user.md) | `true` | `{}` | `[]` |
| `icons/generic/bell` | [7002:19315](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7002-19315) | `Frame 14764 / Group 14764` | [icons/generic/bell](icons-generic-bell.md) | `true` | `{}` | `[]` |
| `icons/line/bell` | [I7002:19315;960:116552](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7002-19315;960-116552) | `Frame 14764 / Group 14764 / icons/generic/bell` | `Bell` | `true` | `{}` | `[]` |

Source text samples (not recommended copy):

| Layer | Sample node | Text | Parent path | References | Owning variants |
| --- | --- | --- | --- | --- | --- |
| `DW` | [I3824:33439;6612:34912;3903:20649](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I3824-33439;6612-34912;3903-20649) | `D` | `Frame 14764 / UserLogin / icons/avatar/user` | `{}` | `[]` |
| `Daniel Wang` | [I3824:33439;3824:22168](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I3824-33439;3824-22168) | `Daniel Wang` | `Frame 14764 / UserLogin` | `{}` | `[]` |
| `number` | [7003:21186](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7003-21186) | `1` | `Frame 14764 / Group 14764 / Badge` | `{}` | `[]` |

Dependency identities from the published graph:

| Original name | External | Source node ID | Asset key |
| --- | --- | --- | --- |
| `IconButton/Error/Xs/Enabled` | `true` | `Not exposed` | `ded5ee4bff18ef1d888c6dd0a45e847acba7f701` |
| `_Logo/aquauni` | `false` | `273:19880` | `b65b136bbaba0ea07d03488f871fa53771fd1a7c` |
| `UserLogin` | `false` | `3824:22170` | `78e0d80e39173758d658c25dd681385d82a14273` |
| `icons/generic/bell` | `false` | `985:129865` | `d8400a05c6a582ba0bb498d2bc0a176d140f3a92` |


## Variants

No variant properties returned for this published node. Further variation: **Needs design review**.


## Properties

| Original property name | Figma type | Source key | Default | Additional source metadata |
| --- | --- | --- | --- | --- |
| `menuContent` | `SLOT` | `menuContent#7002:0` | `-1:-1` | `{}` |

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

**Needs design review** — no explicit state property was returned. State-like text in the component name is a source label only.

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `280` × `887` Figma canvas units.

Explicit responsive configuration was not exposed in the published property list: **Needs design review**.

Raw auto-layout mode, sizing/constraint flags, reflow rules, breakpoints, and interactions: **Needs design review**. Metadata coordinates alone do not establish these rules.

## Accessibility

**Needs design review** — no component-specific accessibility specification or compliance test was verified. Semantic roles, accessible names, focus order, keyboard support, contrast, target size, and assistive-technology behavior require explicit evidence. Visual state names and screenshots do not establish compliance.

## Design tokens

**Needs design review** — no component-scoped variable-definition response has been collected for this node.

See the [shared token snapshot](../tokens/README.md). Mode IDs, alias targets, and individual property-to-variable bindings were not verified here. Equal observed values do not prove alias relationships.

## Figma reference

File key: `01imXcjljmBfqXhqFmv4kz`.

Component: [_Nav/base](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=3824-33443) — node `3824:33443`.

Page: [🧩 Landmarks](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1621-252918) — node `1621:252918`.

Published asset key: `03c6ad28d3db63b57388046f66d98f082785c0a2`.

Observation date: 15 October 2026 (Australia/Melbourne).

Evidence: [get_metadata-1621-252918.json](../sources/figma/component-evidence/get_metadata-1621-252918.json) — `get_metadata`, observed `2026-10-15T03:33:47.746771+00:00`.

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
