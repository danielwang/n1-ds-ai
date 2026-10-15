---
title: "promptfield"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "4325:17649"
figma_node_type: "COMPONENT_SET"
figma_page_id: "0:10803"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# promptfield

## Overview

Original Figma name: `promptfield`. Published node type: `COMPONENT_SET`. Source page: `🧩  Components` ([0:10803](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `icons/generic/plus` | [5001:13732](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5001-13732) | `prefix / attachment` | [icons/generic/plus](icons-generic-plus.md) | `true` | `{}` | `["Type=default", "Type=Incognito", "Type=focused", "Type=dictating", "Type=Voice"]` |
| `Chat/CTA` | [5001:13739](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5001-13739) | `last` | [Chat/CTA](chat-cta.md) | `true` | `{}` | `["Type=default", "Type=Incognito", "Type=focused", "Type=dictating", "Type=Voice"]` |
| `icons/agent/Send` | [I5001:13739;4415:28637](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5001-13739;4415-28637) | `last / Chat/CTA` | [icons/agent/Send](icons-agent-send.md) | `true` | `{}` | `["Type=default", "Type=Incognito", "Type=focused", "Type=dictating"]` |
| `icons/line/Send` | [I5001:13739;4415:28637;960:116575](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5001-13739;4415-28637;960-116575) | `last / Chat/CTA / icons/agent/Send` | `Plane` | `true` | `{}` | `["Type=default", "Type=Incognito", "Type=focused", "Type=dictating"]` |
| `icons/agent/mic` | [5001:13738](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5001-13738) | `last / prompts` | [icons/agent/mic](icons-agent-mic.md) | `true` | `{}` | `["Type=default", "Type=Incognito", "Type=focused", "Type=dictating", "Type=Voice"]` |
| `Microphone` | [I5001:13738;1119:92228](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5001-13738;1119-92228) | `last / prompts / icons/agent/mic` | `Microphone` | `true` | `{}` | `["Type=default", "Type=Incognito", "Type=focused", "Type=dictating", "Type=Voice"]` |
| `icons/generic/plus` | [5013:34272](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5013-34272) | `Frame 14814 / prefix / attachment` | [icons/generic/plus](icons-generic-plus.md) | `true` | `{}` | `["Type=multiline", "Type=with attachments", "Type=with capability"]` |
| `icons/agent/mic` | [5013:34274](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5013-34274) | `Frame 14814 / last` | [icons/agent/mic](icons-agent-mic.md) | `false` | `{}` | `["Type=multiline", "Type=with attachments", "Type=with capability"]` |
| `icons/agent/mic` | [5013:34277](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5013-34277) | `Frame 14814 / last / prompts` | [icons/agent/mic](icons-agent-mic.md) | `true` | `{}` | `["Type=multiline", "Type=with attachments", "Type=with capability"]` |
| `Microphone` | [I5013:34277;1119:92228](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5013-34277;1119-92228) | `Frame 14814 / last / prompts / icons/agent/mic` | `Microphone` | `true` | `{}` | `["Type=multiline", "Type=with attachments", "Type=with capability"]` |
| `Chat/CTA` | [5013:34278](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5013-34278) | `Frame 14814 / last` | [Chat/CTA](chat-cta.md) | `true` | `{}` | `["Type=multiline", "Type=with attachments", "Type=with capability"]` |
| `icons/agent/Send` | [I5013:34278;4415:28637](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5013-34278;4415-28637) | `Frame 14814 / last / Chat/CTA` | [icons/agent/Send](icons-agent-send.md) | `true` | `{}` | `["Type=multiline", "Type=with attachments", "Type=with capability"]` |
| `icons/line/Send` | [I5013:34278;4415:28637;960:116575](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5013-34278;4415-28637;960-116575) | `Frame 14814 / last / Chat/CTA / icons/agent/Send` | `Plane` | `true` | `{}` | `["Type=multiline", "Type=with attachments", "Type=with capability"]` |
| `icons/generic/close` | [5013:34349](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5013-34349) | `Frame 14814 / Group 14777` | [icons/generic/close](icons-generic-close.md) | `true` | `{}` | `["Type=with attachments"]` |
| `icons/generic/close` | [5013:34344](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5013-34344) | `Frame 14814 / Group 14778` | [icons/generic/close](icons-generic-close.md) | `true` | `{}` | `["Type=with attachments"]` |
| `icons/generic/close` | [5273:9829](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5273-9829) | `Frame 14814 / Group 14779` | [icons/generic/close](icons-generic-close.md) | `true` | `{}` | `["Type=with attachments"]` |
| `Chip` | [5014:14174](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5014-14174) | `Frame 14814 / prefix` | [Chip](chip.md) | `true` | `{}` | `["Type=with capability"]` |
| `✳️ icon` | [I5014:14174;1680:123820](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5014-14174;1680-123820) | `Frame 14814 / prefix / Chip` | [icons/generic/Research](icons-generic-research.md) | `true` | `{"visible": "👁️ Icon#1680:360", "mainComponent": "↳ icon#2539:119"}` | `["Type=with capability"]` |
| `icons/generic/telescope` | [I5014:14174;1680:123820;4271:28562](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5014-14174;1680-123820;4271-28562) | `Frame 14814 / prefix / Chip / ✳️ icon` | `Telescope` | `true` | `{}` | `["Type=with capability"]` |
| `action` | [I5014:14174;1412:131277](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5014-14174;1412-131277) | `Frame 14814 / prefix / Chip` | [icons/generic/close-2](icons-generic-close-2.md) | `true` | `{"visible": "👁️ Action#1680:71", "mainComponent": "↳ action icon#1680:1227"}` | `["Type=with capability"]` |
| `Chip` | [6506:11345](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6506-11345) | `Frame 14814 / prefix` | [Chip](chip.md) | `false` | `{}` | `["Type=with capability"]` |
| `✳️ icon` | [6693:7258](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6693-7258) | `Frame 14814 / prefix / Chip` | [AI Brands/icon/Gemini](ai-brands-icon-gemini.md) | `true` | `{}` | `["Type=with capability"]` |
| `icons/generic/Chevron Down` | [6693:7262](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6693-7262) | `Frame 14814 / prefix / Chip / Frame 14898` | [icons/generic/Chevron Down](icons-generic-chevron-down.md) | `true` | `{}` | `["Type=with capability"]` |
| `action` | [6693:7264](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6693-7264) | `Frame 14814 / prefix / Chip / Frame 14898` | [icons/generic/close-2](icons-generic-close-2.md) | `true` | `{}` | `["Type=with capability"]` |
| `icons/generic/Soundwave` | [I7223:6557;7202:21446](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7223-6557;7202-21446) | `last / Chat/CTA` | [icons/generic/Soundwave](icons-generic-soundwave.md) | `true` | `{}` | `["Type=Voice"]` |
| `Soundwave` | [I7223:6557;7202:21446;7202:17512](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7223-6557;7202-21446;7202-17512) | `last / Chat/CTA / icons/generic/Soundwave` | `Soundwave` | `true` | `{}` | `["Type=Voice"]` |

Source text samples (not recommended copy):

| Layer | Sample node | Text | Parent path | References | Owning variants |
| --- | --- | --- | --- | --- | --- |
| `Type a message` | [5001:13733](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5001-13733) | `Type a message` | `prefix` | `{}` | `["Type=default", "Type=Incognito", "Type=focused"]` |
| `This is dictating mode looks like` | [5013:34251](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5013-34251) | `This is dictating mode looks like` | `prefix` | `{}` | `["Type=dictating"]` |
| `Condimentum duis amet nulla egestas mattis vestibulum. Pellentesque posuere pretium ac gravida sit quis maecenas aliquam laoreet. Eget maecenas laoreet neque phasellus eget lacinia. Pellentesque at accumsan accumsan sagittis volutpat adipiscing integer. In porttitor tincidunt tortor fermentum et amet euismod id. Pharetra sed at molestie pulvinar. Enim mattis nibh leo diam magnis interdum praesent leo. Non mi tristique accumsan fermentum arcu dictum viverra. Ac volutpat lobortis sodales tellus viverra nunc egestas id aenean. Sed elit blandit donec urna erat. Varius nunc egestas ultrices sed. Id eget ut et consequat convallis volutpat ultricies sed rhoncus. Sapien placerat vitae.` | [5013:34267](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5013-34267) | `Condimentum duis amet nulla egestas mattis vestibulum. Pellentesque posuere pretium ac gravida sit quis maecenas aliquam laoreet. Eget maecenas laoreet neque phasellus eget lacinia. Pellentesque at accumsan accumsan sagittis volutpat adipiscing integer. In porttitor tincidunt tortor fermentum et amet euismod id. Pharetra sed at molestie pulvinar. Enim mattis nibh leo diam magnis interdum praesent leo. Non mi tristique accumsan fermentum arcu dictum viverra. Ac volutpat lobortis sodales tellus viverra nunc egestas id aenean. Sed elit blandit donec urna erat. Varius nunc egestas ultrices sed. Id eget ut et consequat convallis volutpat ultricies sed rhoncus. Sapien placerat vitae.` | `root` | `{}` | `["Type=multiline", "Type=with attachments"]` |
| `lung cancer ALK and treatments` | [5014:13211](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5014-13211) | `lung cancer ALK and treatments` | `root` | `{}` | `["Type=with capability"]` |
| `label` | [I5014:14174;1412:131276](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I5014-14174;1412-131276) | `Deep Research` | `Frame 14814 / prefix / Chip / label container` | `{}` | `["Type=with capability"]` |
| `label` | [6693:7260](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=6693-7260) | `Create image` | `Frame 14814 / prefix / Chip / label container` | `{}` | `["Type=with capability"]` |
| `Let’s discover what only you could ask` | [7223:6555](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7223-6555) | `Let’s discover what only you could ask ` | `prefix` | `{}` | `["Type=Voice"]` |

Dependency identities from the published graph:

| Original name | External | Source node ID | Asset key |
| --- | --- | --- | --- |
| `icons/generic/plus` | `false` | `0:8105` | `c294efa855b9f004905d6c4d72c12ef405818343` |
| `Chat/CTA` | `false` | `4415:30687` | `e424966c1f362ce9427e869c960a1647c843837f` |
| `icons/agent/mic` | `false` | `1119:92239` | `75a001b7c0061391c0187729d7d5f47d63277c9e` |
| `icons/generic/close` | `false` | `0:8301` | `bd531770f72bde0a78c3102c9dfafbdde59166b6` |
| `Chip` | `false` | `86:5732` | `7c63c229332e9427a24eb9a6e41e835449bc7ed1` |
| `AI Brands/icon/Gemini` | `false` | `4912:21245` | `8d1c13dda7b412a32b7e9627b06c8296173fa305` |
| `icons/generic/Chevron Down` | `false` | `1225:39098` | `9378a96842cb1c6b7f955ff389321e1431055a0a` |
| `icons/generic/close-2` | `false` | `0:8067` | `55f88b77400acf0b875c1400475d94ddf56e909d` |


## Variants

| Property | Published options | Published default |
| --- | --- | --- |
| `Type` | `["default", "dictating", "with attachments", "multiline", "with capability", "focused", "Incognito", "Voice"]` | `default` |

8 member nodes directly observed in metadata. This is not a Cartesian-product estimate. Names and actual dimensions are preserved:

| Original member name | Node | Width | Height |
| --- | --- | --- | --- |
| `Type=default` | [5001:13728](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5001-13728) | `850` | `52` |
| `Type=Incognito` | [5226:14380](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5226-14380) | `850` | `52` |
| `Type=focused` | [5016:14641](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5016-14641) | `850` | `52` |
| `Type=dictating` | [5013:34246](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5013-34246) | `850` | `52` |
| `Type=multiline` | [5013:34266](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5013-34266) | `850` | `191` |
| `Type=with attachments` | [5013:34301](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5013-34301) | `850` | `346` |
| `Type=with capability` | [5014:13210](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=5014-13210) | `850` | `83` |
| `Type=Voice` | [7223:6550](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7223-6550) | `850` | `52` |


## Properties

| Original property name | Figma type | Source key | Default | Additional source metadata |
| --- | --- | --- | --- | --- |
| `Type` | `VARIANT` | `Type` | `default` | `{"variantOptions": ["default", "dictating", "with attachments", "multiline", "with capability", "focused", "Incognito", "Voice"]}` |

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

**Needs design review** — no explicit state property was returned. State-like text in the component name is a source label only.

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `920` × `1130` Figma canvas units.

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

Component: [promptfield](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=4325-17649) — node `4325:17649`.

Page: [🧩  Components](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803) — node `0:10803`.

Published asset key: `625328c3a3e033ab3f45f72c757c25162d3efe5c`.

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
