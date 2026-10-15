# Design-system review workflow

Read when assessing an N1 UI, design, screenshot, or implementation.

## Compare against applicable evidence

Identify the reviewed screen/state, user task, and available artifacts. Inspect code or a running UI when behavior is in scope and those artifacts are available. A screenshot supports visual observations, not keyboard or assistive-technology conclusions.

Load the relevant component specifications, token records, [patterns](system/patterns/index.md), [writing guidance](system/foundations/voice-and-tone.md), and [accessibility status](system/foundations/accessibility.md). Verify source context and approval status before asserting a requirement. External links in a component are references; they are not automatically adopted N1 specifications.

Check original component/variant selection, supported property options and actual combinations, observed dimensions/layout context, value-bearing token usage, and applicable copy and interaction guidance. Confirm runtime APIs against actual code. Separate code-generated styling from source definitions and distinguish documented example dimensions from responsive rules.

## Classify findings accurately

| Classification | Evidence needed |
| --- | --- |
| Verified source mismatch | Applicable source/node/definition and an observed conflicting UI or code value |
| Verified requirement violation | An approved requirement and evidence the reviewed implementation violates it |
| Demonstrated accessibility issue | Reproducible observation, method, affected interaction, and impact; identify any standard used rather than claiming it is approved N1 policy |
| Untested concern | A plausible issue with the missing test clearly stated |
| Needs design review | Requirement, approval, applicability, behavior, or source details are unverified |
| Proposed improvement/deviation | Rationale and expected impact, clearly separated from a compliance finding |

Use a concise finding record: **location/state → observation → source/requirement and status → user impact → suggested correction → verification**. Assign urgency from demonstrated impact and scope; avoid invented N1 severity rules. Existing accepted deviations should retain their recorded scope and authority.

Report findings before recommendations, followed by tested areas and coverage limits. Do not certify accessibility or design-system compliance from the absence of findings. Fix issues when requested and verify the changed behavior; preserve evidence and explain any unresolved deviation.
