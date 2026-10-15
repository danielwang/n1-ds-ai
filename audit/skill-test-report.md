# N1 Agent Settings skill test

Date: 15 October 2026. Skill invoked: [`n1-design-system`](../skills/n1-design-system/SKILL.md).

**Outcome: source/preflight checks completed; working UI and rendered accessibility testing are blocked by a missing frontend project and executable component library.** This is not a successful end-to-end UI test. No substitute framework, component API, or implementation was created. The existing-project question is pending.

The user explicitly requires WCAG 2.2 AA for this scenario. That target applies to this task even though the repository has no approved global N1 conformance policy. See the [W3C specification](https://www.w3.org/TR/WCAG22/).

## Environment and scope

Reviewed the bundled design entry point, generation/review workflows, foundations, patterns, token coverage, and relevant component specifications. The workspace has no frontend entry point, `package.json`, application lockfile, installed app dependencies, build script, or executable N1 component package. Node v20.17.0 and npm 10.8.2 are present; their presence does not supply a frontend framework. MUI links in Figma are documentation references, not installed N1 code or verified APIs.

The user's instruction forbids inventing a framework or component implementation. Therefore a working Agent Settings page cannot be implemented faithfully until the existing project path/repository and component package are provided. Building a new React app or relabelling native controls as N1 components would violate that constraint.

No product field schema, persistence endpoint, permissions model, or existing Agent Settings flow was supplied. Those should be read from the actual project rather than fabricated. No Figma writes were performed.

## 1. Components used

**Runtime components used: none; no UI exists yet.** The following are source-verified candidates, not implemented or newly approved components:

| Component | Verified Figma selection | Actual member | Intended test role, pending project context |
| --- | --- | --- | --- |
| [Button](../components/button.md) | `Variant=Contained, Color=Inherit, Size=M, State=Enabled` | `1667:129888` | Candidate action control; actual save action/API not established |
| [TextField](../components/input.md) | `Size=LG, State=Enabled, 👁️ Value=True` | Recorded in [results](skill-test/results.json) | Candidate field; actual Agent Settings field schema not established |
| TextField | `Size=LG, State=Focused, 👁️ Value=True` | `1670:171163` | Verified visual-state option; keyboard behavior still untested |
| [Card](../components/card.md) | `Type=Container, Title=No` | `141:26396` | Candidate content grouping; fixed example bounds are not responsive rules |

[Templates](../components/templates.md) and the [pattern index](../patterns/index.md) provide composition references. Their mobile/layout labels do not define switching breakpoints. The published catalog lacks a complete approval register, so “approved component” status cannot be claimed solely from publication.

### Live Figma comparison

Official MCP access was verified against file `01imXcjljmBfqXhqFmv4kz`, initial source node `915:56433`. Current member identities, names, and dimensions matched the bundled metadata for Button `1667:129167`, TextField `194:62777`, and Card `1026:27381`. The current TextField variable-definition map matched the retained snapshot. Live TextField and Button Code Connect queries returned empty maps; no implementation reference was returned by those queries.

See [live evidence](skill-test/figma/) and [comparison results](skill-test/results.json). This confirms the inspected metadata, not every visual state, prototype behavior, or a runtime implementation.

## 2. Tokens used

**Runtime tokens applied: none.** Source colour pairs were checked independently of an interface:

| Existing foreground token | Existing background token | Values | Calculated ratio | Result for stated context |
| --- | --- | --- | --- | --- |
| `text/primary` | `background/paper` | `#161c24` / `#ffffff` | 17.13:1 | Above normal-text threshold |
| `text/secondary` | `background/paper` | `#637381` / `#ffffff` | 4.88:1 | Above normal-text threshold |
| `global/inherit/color` | `global/inherit/bg` | `#ffffff` / `#212b36` | 14.35:1 | Above normal-text threshold |
| `text/disabled` | `background/paper` | `#919eab` / `#ffffff` | 2.73:1 | Below normal-text threshold if used for an enabled field's label |
| `components/textfield/outline` | `background/paper` | `#c4cdd5` / `#ffffff` | 1.61:1 | Below 3:1 if this boundary is necessary to identify the control |

Values come from component-scoped `get_variable_defs` evidence; no aliases or new token names were synthesized. Arithmetic compares unrounded ratios. Normal text generally requires 4.5:1; an inactive-control exemption depends on actual state, not a token named `disabled`. [W3C contrast guidance](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html)

The retained enabled TextField sample renders `Label` with `text/disabled` on white. This exposes a source contrast concern to resolve before implementation, not a tested failure in a generated page. Its light outline also needs contextual review: the non-text requirement depends on which visual information identifies the control. [W3C non-text contrast guidance](https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html)

No undocumented spacing, radius units, theme aliases, CSS token identifiers, or responsive thresholds were introduced. The shared token snapshot remains partial.

## 3. Design principles applied

The authored [Design for Real Work](../foundations/design-principles.md) principle directs attention to meaningful task completion, reduced effort, time saved, and cognitive load. Here it supports preserving a usable existing workflow and avoiding fabricated APIs or settings. It is source-authored guidance with unrecorded formal approval status.

The current task's accessibility target and keyboard requirement remain mandatory for the eventual implementation. Proposed voice-and-tone guidance remains labelled proposed; no production copy or audience-specific terminology has been presented as approved N1 writing.

## 4. Compliance findings and checks

| Area | Result | Evidence or limitation |
| --- | --- | --- |
| Component accuracy | Source selection checks pass; runtime untested | Actual member combinations verified; no app to inspect |
| Token compliance | Existing values preserved; runtime untested | Five contrast calculations; full aliases/modes unresolved |
| Visual consistency | Metadata comparison passes; rendered comparison not run | Three live component comparisons; no UI screenshot |
| Interaction consistency | Not tested | No executable controls, persistence flow, or interaction specification |
| UX writing | Guidance reviewed; UI copy not generated | Approved content policy and actual field schema unavailable |
| Accessibility | Source-level concerns identified; conformance untested | Contrast arithmetic is not a WCAG audit of a complete page |

Source regression tests passed 12 cases: supported Button/TextField/Card selections, focused TextField, unsupported focused Button, nonexistent Cartesian combination, wrong case/type, non-variant properties, and missing component. The key negative case is `Button / Contained / Primary / M / Disabled`: its options exist separately, but no actual member matches. Treating the option lists as a full Cartesian product would be incorrect.

Commands run:

```sh
python3 scripts/test_n1_skill_sources.py
python3 skills/n1-design-system/scripts/validate_package.py
python3 scripts/validate_components.py
python3 scripts/validate_tokens.py
python3 -m py_compile skills/n1-design-system/scripts/check_selection.py scripts/test_n1_skill_sources.py
git diff --check
```

The available skill-creator `quick_validate.py` was also run against the revised skill. The revised ZIP was re-created and checked by extraction into an isolated temporary directory. These are skill, source-data, syntax, and packaging checks; they are not frontend checks.

**Not run:** frontend build, application unit/integration tests, browser rendering, axe/browser accessibility scanning, keyboard automation, or assistive-technology testing. No existing app or project test harness is available to run them against. No compliance pass is claimed.

### Checks needed once the project is available

Use the real app's build and test scripts, then its existing browser/accessibility tooling where available. Compare rendered states with the exact Figma members, preserving documented deviations.

Human testing remains necessary for keyboard task completion, meaningful focus order and visibility, focus not obscured by sticky content, screen-reader names/errors/status feedback, zoom/reflow, actual contrast across states, and responsive usability. Include WCAG 2.2 AA's focus-not-obscured and target-size criteria, with their applicability and exceptions. [Focus guidance](https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-minimum.html), [target-size guidance](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html)

Save/retry/error behavior, focus after validation failure, unsaved changes, and any dialog behavior need the actual product flow. Automated checks alone do not establish complete-page conformance.

## 5. Missing or unclear specifications

1. Existing frontend repository/path and executable N1 component library, including real imports/APIs and test commands — **implementation blocker**.
2. Agent Settings schema, backend/persistence contract, existing validation and permissions behavior — **Needs design review / project evidence**.
3. Component approval register and accepted deviations — **approval unverified**.
4. Responsive switching, grid, overflow, raw auto-layout, and keyboard/focus specifications — **Needs design review**.
5. Complete semantic token roles, mode/alias graph, and units — **partially exposed**.
6. Approved N1 writing guidance and institutional accessibility policy — **not supplied**. The task-specific WCAG 2.2 AA target still applies.
7. Resolution of source label/boundary contrast concerns in the intended enabled state — **requires review and rendered verification**.

## 6. Skill improvements and retest

Instruction review found that “an isolated implementation may be justified” could be misapplied when a user explicitly prohibits a new framework or substitute components. No incorrect UI was generated in this run; the ambiguity was corrected before implementation.

Updated the [skill](../skills/n1-design-system/SKILL.md) and [generation workflow](../skills/n1-design-system/references/generation.md), added [implementation preflight](../skills/n1-design-system/references/implementation-preflight.md), and added [actual-member selection validation](../skills/n1-design-system/scripts/check_selection.py). The changes:

- Require the existing project/package when a substitute stack or component implementation is prohibited.
- Preserve an explicit task conformance target even when global N1 policy is missing.
- Require contextual contrast checks rather than assuming token names or publication imply accessibility.
- Reject unsupported Figma combinations without inventing runtime APIs.

The relevant source regression and packaging checks were rerun after those changes; see [machine-readable results](skill-test/results.json). A working UI and its UX/accessibility validation remain pending the existing frontend project. This report must be updated with actual implementation and browser evidence before this scenario is reported as completed.
