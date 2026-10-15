---
title: "PromptVoice"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "7357:57485"
figma_node_type: "COMPONENT_SET"
figma_page_id: "0:10803"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# PromptVoice

## Overview

Original Figma name: `PromptVoice`. Published node type: `COMPONENT_SET`. Source page: `🧩  Components` ([0:10803](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `VioceControl` | [7357:57419](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7357-57419) | `prefix` | [VioceControl](viocecontrol.md) | `true` | `{}` | `["Status=Listening", "Status=Speaking / Muted", "Status=Speaking / Cancel+Muted", "Status=Listening / Cancel", "Status=Speaking / Cancel", "Status=Speaking", "Status=Thinking"]` |
| `Control/Voice` | [I7357:57419;7226:14056](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57419;7226-14056) | `prefix / VioceControl` | [Control/Voice](control-voice.md) | `true` | `{}` | `["Status=Listening", "Status=Speaking / Muted", "Status=Speaking / Cancel+Muted", "Status=Listening / Cancel", "Status=Speaking / Cancel", "Status=Speaking", "Status=Thinking"]` |
| `icons/agent/mic` | [I7357:57419;7226:14056;7226:7906](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57419;7226-14056;7226-7906) | `prefix / VioceControl / Control/Voice` | [icons/agent/mic](icons-agent-mic.md) | `true` | `{}` | `["Status=Listening", "Status=Speaking / Muted", "Status=Speaking", "Status=Thinking"]` |
| `Microphone` | [I7357:57419;7226:14056;7226:7906;1119:92228](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57419;7226-14056;7226-7906;1119-92228) | `prefix / VioceControl / Control/Voice / icons/agent/mic` | `Microphone` | `true` | `{}` | `["Status=Listening", "Status=Speaking / Muted", "Status=Speaking", "Status=Thinking"]` |
| `icons/generic/Volume` | [I7357:57419;7226:14049;7227:54413](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57419;7226-14049;7227-54413) | `prefix / VioceControl / Control/Voice` | [icons/generic/Volume](icons-generic-volume.md) | `true` | `{}` | `["Status=Listening", "Status=Speaking / Cancel+Muted", "Status=Listening / Cancel", "Status=Speaking", "Status=Thinking"]` |
| `icons/generic/Tuning` | [I7357:57419;7226:14048](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57419;7226-14048) | `prefix / VioceControl / settings` | [icons/generic/Tuning](icons-generic-tuning.md) | `true` | `{}` | `["Status=Listening", "Status=Speaking / Muted", "Status=Speaking / Cancel+Muted", "Status=Listening / Cancel", "Status=Speaking / Cancel", "Status=Speaking", "Status=Thinking"]` |
| `VoiceStatus` | [7357:57420](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7357-57420) | `prefix` | [VoiceStatus](voicestatus.md) | `true` | `{}` | `["Status=Listening", "Status=Speaking / Muted", "Status=Speaking / Cancel", "Status=Speaking"]` |
| `Chat/CTA` | [7357:57422](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7357-57422) | `last` | [Chat/CTA](chat-cta.md) | `true` | `{}` | `["Status=Listening", "Status=Speaking / Muted", "Status=Speaking / Cancel+Muted", "Status=Listening / Cancel", "Status=Speaking / Cancel", "Status=Speaking", "Status=Connecting", "Status=Thinking"]` |
| `icons/generic/Volume Cross` | [I7357:57426;7226:14049;7227:58298](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57426;7226-14049;7227-58298) | `prefix / VioceControl / Control/Voice` | [icons/generic/Volume Cross](icons-generic-volume-cross.md) | `true` | `{}` | `["Status=Speaking / Muted", "Status=Speaking / Cancel"]` |
| `icons/generic/Microphone cross` | [I7357:57433;7226:14056;7226:7900](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57433;7226-14056;7226-7900) | `prefix / VioceControl / Control/Voice` | [icons/generic/Microphone cross](icons-generic-microphone-cross.md) | `true` | `{}` | `["Status=Speaking / Cancel+Muted", "Status=Listening / Cancel", "Status=Speaking / Cancel"]` |
| `VoiceStatus` | [7357:57435](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7357-57435) | `prefix / Group 14822` | [VoiceStatus](voicestatus.md) | `true` | `{}` | `["Status=Speaking / Cancel+Muted"]` |
| `VoiceStatus` | [7357:57443](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7357-57443) | `prefix / Group 14823` | [VoiceStatus](voicestatus.md) | `true` | `{}` | `["Status=Listening / Cancel", "Status=Connecting", "Status=Thinking"]` |
| `VioceControl` | [7357:57465](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7357-57465) | `Frame 14814 / prefix` | [VioceControl](viocecontrol.md) | `true` | `{}` | `["Status=Listening / With Transcript"]` |
| `Control/Voice` | [I7357:57465;7226:14056](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57465;7226-14056) | `Frame 14814 / prefix / VioceControl` | [Control/Voice](control-voice.md) | `true` | `{}` | `["Status=Listening / With Transcript"]` |
| `icons/agent/mic` | [I7357:57465;7226:14056;7226:7906](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57465;7226-14056;7226-7906) | `Frame 14814 / prefix / VioceControl / Control/Voice` | [icons/agent/mic](icons-agent-mic.md) | `true` | `{}` | `["Status=Listening / With Transcript"]` |
| `Microphone` | [I7357:57465;7226:14056;7226:7906;1119:92228](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57465;7226-14056;7226-7906;1119-92228) | `Frame 14814 / prefix / VioceControl / Control/Voice / icons/agent/mic` | `Microphone` | `true` | `{}` | `["Status=Listening / With Transcript"]` |
| `icons/generic/Volume` | [I7357:57465;7226:14049;7227:54413](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57465;7226-14049;7227-54413) | `Frame 14814 / prefix / VioceControl / Control/Voice` | [icons/generic/Volume](icons-generic-volume.md) | `true` | `{}` | `["Status=Listening / With Transcript"]` |
| `icons/generic/Tuning` | [I7357:57465;7226:14048](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57465;7226-14048) | `Frame 14814 / prefix / VioceControl / settings` | [icons/generic/Tuning](icons-generic-tuning.md) | `true` | `{}` | `["Status=Listening / With Transcript"]` |
| `VoiceStatus` | [7357:57466](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7357-57466) | `Frame 14814 / prefix` | [VoiceStatus](voicestatus.md) | `true` | `{}` | `["Status=Listening / With Transcript"]` |
| `Chat/CTA` | [7357:57468](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7357-57468) | `Frame 14814 / last` | [Chat/CTA](chat-cta.md) | `true` | `{}` | `["Status=Listening / With Transcript"]` |

Source text samples (not recommended copy):

| Layer | Sample node | Text | Parent path | References | Owning variants |
| --- | --- | --- | --- | --- | --- |
| `Listening` | [I7357:57420;7248:11516](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57420;7248-11516) | `Listening` | `prefix / VoiceStatus` | `{}` | `["Status=Listening"]` |
| `Speaking` | [I7357:57427;7249:6082](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57427;7249-6082) | `Speaking` | `prefix / VoiceStatus` | `{}` | `["Status=Speaking / Muted", "Status=Speaking / Cancel", "Status=Speaking"]` |
| `Speaking` | [I7357:57435;7249:6082](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57435;7249-6082) | `Speaking` | `prefix / Group 14822 / VoiceStatus` | `{}` | `["Status=Speaking / Cancel+Muted"]` |
| `Listening` | [I7357:57443;7248:11516](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57443;7248-11516) | `Listening` | `prefix / Group 14823 / VoiceStatus` | `{}` | `["Status=Listening / Cancel"]` |
| `Condimentum duis amet nulla egestas mattis vestibulum. Pellentesque posuere pretium ac gravida sit quis maecenas aliquam laoreet. Eget maecenas laoreet neque phasellus eget lacinia. Pellentesque at accumsan accumsan sagittis volutpat adipiscing integer. In porttitor tincidunt tortor fermentum et amet euismod id. Pharetra sed at molestie pulvinar. Enim mattis nibh leo diam magnis interdum praesent leo. Non mi tristique accumsan fermentum arcu dictum viverra. Ac volutpat lobortis sodales tellus viverra nunc egestas id aenean. Sed elit blandit donec urna erat. Varius nunc egestas ultrices sed. Id eget ut et consequat convallis volutpat ultricies sed rhoncus. Sapien placerat vitae.` | [7357:57462](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7357-57462) | `Condimentum duis amet nulla egestas mattis vestibulum. Pellentesque posuere pretium ac gravida sit quis maecenas aliquam laoreet. Eget maecenas laoreet neque phasellus eget lacinia. Pellentesque at accumsan accumsan sagittis volutpat adipiscing integer. In porttitor tincidunt tortor fermentum et amet euismod id. Pharetra sed at molestie pulvinar. Enim mattis nibh leo diam magnis interdum praesent leo. Non mi tristique accumsan fermentum arcu dictum viverra. Ac volutpat lobortis sodales tellus viverra nunc egestas id aenean. Sed elit blandit donec urna erat. Varius nunc egestas ultrices sed. Id eget ut et consequat convallis volutpat ultricies sed rhoncus. Sapien placerat vitae.` | `root` | `{}` | `["Status=Listening / With Transcript"]` |
| `Listening` | [I7357:57466;7248:11516](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57466;7248-11516) | `Listening` | `Frame 14814 / prefix / VoiceStatus` | `{}` | `["Status=Listening / With Transcript"]` |
| `Connecting` | [I7357:57473;7249:6149](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57473;7249-6149) | `Connecting` | `prefix / Group 14823 / VoiceStatus` | `{}` | `["Status=Connecting"]` |
| `Thinking` | [I7357:57481;7249:6015](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I7357-57481;7249-6015) | `Thinking` | `prefix / Group 14823 / VoiceStatus` | `{}` | `["Status=Thinking"]` |

Dependency identities from the published graph:

| Original name | External | Source node ID | Asset key |
| --- | --- | --- | --- |
| `VioceControl` | `false` | `7247:14250` | `69846ff10b115402ef1b88b29688c8cff4a482e8` |
| `VoiceStatus` | `false` | `7248:11565` | `84c0a2073b65e6d20fdce614154dd1be779f1481` |
| `Chat/CTA` | `false` | `4415:30687` | `e424966c1f362ce9427e869c960a1647c843837f` |


## Variants

| Property | Published options | Published default |
| --- | --- | --- |
| `Status` | `["Listening", "Speaking / Muted", "Speaking / Cancel+Muted", "Listening / Cancel", "Speaking / Cancel", "Speaking", "Listening / With Transcript", "Connecting", "Thinking"]` | `Listening` |


## Properties

| Original property name | Figma type | Source key | Default | Additional source metadata |
| --- | --- | --- | --- | --- |
| `Status` | `VARIANT` | `Status` | `Listening` | `{"variantOptions": ["Listening", "Speaking / Muted", "Speaking / Cancel+Muted", "Listening / Cancel", "Speaking / Cancel", "Speaking", "Listening / With Transcript", "Connecting", "Thinking"]}` |

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

| Source property | Type | Options | Default |
| --- | --- | --- | --- |
| `Status` | `VARIANT` | `["Listening", "Speaking / Muted", "Speaking / Cancel+Muted", "Listening / Cancel", "Speaking / Cancel", "Speaking", "Listening / With Transcript", "Connecting", "Thinking"]` | `Listening` |

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `890` × `898` Figma canvas units.

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

Component: [PromptVoice](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=7357-57485) — node `7357:57485`.

Page: [🧩  Components](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-10803) — node `0:10803`.

Published asset key: `28609e8d4b0f1ff26983edff48032014bf3c4c92`.

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
