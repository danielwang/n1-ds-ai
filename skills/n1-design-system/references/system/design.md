# N1 design system

Status: evidence-based entry point, with explicit review gaps. Reviewed 15 October 2026. This document records source status; it does not confer approval on proposals or extracted examples.

## Overview

N1 (nebulaONE) is an AI platform for higher education institutions, serving students, academic staff, agent creators, administrators, and other institutional users. The product brief for this synthesis calls for clear, accessible, consistent, and trustworthy experiences. These are human-provided goals, not a complete institutional UX or accessibility policy.

Start with the relevant component specification and its source evidence. Preserve unknowns as **Needs design review**.

## Design philosophy

The retained Figma guidance says **“Design for Real Work”**: minimise effort and maximise progress, measured through time saved, tasks completed, and reduced cognitive load. Preserve this authored guidance; its formal approval status was not recorded. See [design principles](foundations/design-principles.md) for the exact text and attribution.

## Design principles

Use the following evidence labels throughout the system:

| Label | Meaning |
| --- | --- |
| Product brief | Human-provided direction from this task |
| Figma-authored | Text explicitly present in the source; approval status separately recorded |
| Figma-derived | Observed values, names, structure, or geometry |
| Repository rule | Instructions for preserving and interpreting evidence |
| Proposed | Suggested guidance awaiting approval; not an N1 requirement |
| Needs design review | Information or applicability not established by available evidence |

No separately approved principle register was found. Consult [design principles](foundations/design-principles.md) before treating an interpretation as policy.

## Visual foundations

Use [visual principles](foundations/visual-principles.md) to navigate colour, typography, dimensions, effects, assets, and layout evidence. Select values and components by documented context. Token names, repeated styling, and generated rendering classes alone do not establish usage rules.

## Design tokens

The [token snapshot](tokens/README.md) contains 45 colour values, two raw typography definitions, one raw radius value, and metadata-only discoveries. It is a partial export. Preserve original names and source attribution; inspect the distinction between value-bearing tokens and extension metadata before consumption.

Collections, modes, aliases, primitive/semantic relationships, and some units remain incompletely exposed. Do not infer aliases from equal values, light/dark modes from names, or units from numeric suffixes. Component-scoped observations may be newer or broader than the earlier shared snapshot; reconcile their source context before reuse.

## Components

The [component index](components/index.md) covers 492 published entries across 12 readable pages, including 112 sets and 380 standalone components. Start with [Button](components/button.md), [TextField](components/input.md), [Dialog](components/dialog.md), [Card](components/card.md), and [Nav](components/navigation.md).

Preserve exact Figma property and variant names. Published properties describe design configuration. Verify implementation APIs against actual code; MCP-generated examples do not establish those APIs. Check [coverage](audit/component-documentation-coverage.md) for inspection depth and query failures.

## Interaction patterns

Use the [pattern index](patterns/index.md) for observed compositions and state labels. No complete interaction-policy set was verified. Keyboard actions, focus movement, validation timing, dismissal, persistence, and AI workflow transitions remain **Needs design review** unless supported by a specific source.

## Accessibility

Accessibility is a product goal. An approved conformance target, component requirements, and test evidence were not supplied. Follow the distinction between existing evidence and proposed review areas in [accessibility](foundations/accessibility.md). Screenshots, state labels, and contrast-tool names do not prove compliance.

## Voice and tone

No approved N1 voice-and-tone guide was found. [Voice and tone](foundations/voice-and-tone.md) records that gap and clearly separates proposed writing guidance from existing source copy. Sample labels are not a global content standard.

## Responsive design

[Templates](components/templates.md) exposes `Layout=Max Width/Fluid` and `Nav=Open/Collapsed`; [Templates/Mobile](components/templates-mobile.md) is a separate source component. Other device-labelled variants are indexed under [responsive evidence](patterns/index.md#responsive-evidence).

These are observed configurations. Breakpoints, automatic switching, reflow, and overflow rules are **Needs design review**. Do not turn example widths into breakpoint definitions or assume every option combination exists.

## Source of truth

Repository operating rules for this documentation:

1. Follow [workspace instructions](AGENTS.md); keep Figma read-only and preserve source identifiers.
2. Use identified Figma nodes/variables for visual and structural facts, with file, node, mode where known, and observation date. Treat extracted files as snapshots; use the [source manifest](sources/figma/manifest.json) to trace them.
3. Use explicitly approved human guidance for UX, content, and accessibility policy within its stated scope. Approval evidence is currently missing; proposals cannot fill that role. Use verified code for implementation APIs.
4. Resolve apparent conflicts by checking identity, scope, version, mode, and approval status. Record both sources and the affected decision. A newer timestamp alone does not settle different contexts or policy conflicts.
5. Correct demonstrable extraction errors against attributable evidence. Refer unresolved source or policy conflicts for design-owner review, preserve both records, and mark the affected decision **Needs design review**. Record the resolution and authority before changing shared guidance.

## Documentation references

- [Design principles](foundations/design-principles.md), [visual principles](foundations/visual-principles.md), [accessibility](foundations/accessibility.md), and [voice and tone](foundations/voice-and-tone.md).
- [Tokens](tokens/README.md), [components](components/index.md), and [patterns](patterns/index.md).
- [Current component inventory](audit/component-inventory.md), [inspection coverage](audit/component-documentation-coverage.md), and [historical audit gaps](audit/documentation-gaps.md).

Missing source materials: approval/version records; the complete N1 principles and brand guide; accessibility policy and test evidence; voice-and-tone and terminology guidance; interaction/prototype specifications; responsive layout rules; a full variable/mode/alias export; verified implementation references; and copies of source-linked external guidance with its intended N1 applicability.
