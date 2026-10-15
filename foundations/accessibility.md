# Accessibility

Status: accessibility is a human-provided product goal. No approved N1 accessibility specification or conformance evidence was found in the reviewed repository. Reviewed 15 October 2026.

## Existing evidence and its limits

- [TextField](../components/input.md) exposes named states including `Focused`, `Error`, `Disabled`, and `Readonly`, plus label/help-text properties. These are design options; they do not verify programmatic names, error announcements, keyboard support, or contrast.
- [Button](../components/button.md), [Dialog](../components/dialog.md), and [Nav](../components/navigation.md) retain visual structure and state evidence. No component-specific compliance claim follows from those observations.
- The source contains [_A11YColorContrastCard](../components/a11ycolorcontrastcard.md) and [_ratio](../components/ratio.md). Their names and variants do not establish a conformance target or test results.
- Example product content mentioning WCAG or accessibility auditing is source sample text, not an adopted N1 policy.

## Approved requirements

**Needs design review:** applicable standard/version, target level, platform and workflow scope, institutional requirements, exceptions, and accountable approver. No numerical contrast, target-size, text-size, or breakpoint thresholds are asserted by this document.

Repository rule: report a requirement as approved only with an attributable policy record. Report a feature as tested only with applicable test evidence. Preserve uncertainty separately from observed failures; lack of evidence is not a finding of noncompliance.

## Proposed review areas — not approved N1 requirements

Use these as review prompts pending an approved specification:

- Semantic structure, accessible names, labels, instructions, and error association.
- Keyboard operation, visible focus, focus movement, and dialog return-focus behavior.
- Screen-reader announcements for asynchronous AI activity and status changes.
- Contrast across actual states and themes; information conveyed through more than colour alone.
- Zoom, reflow, text adaptation, motion preferences, and operation without pointer precision.
- Voice controls, transcript alternatives, and recovery from permission or connection failures.

These prompts do not establish specific interaction behavior, pass criteria, or a compliance claim.

## Evidence needed

Provide the approved policy, supported browser/assistive-technology matrix, component interaction specifications, test procedures and results, exception decisions, and owner/version records. See [component coverage](../audit/component-documentation-coverage.md) for what has actually been inspected and [source-of-truth rules](../design.md#source-of-truth) for handling conflicts.
