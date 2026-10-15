# N1 pattern index

Status: index of Figma-observed compositions and state labels. No complete approved interaction-pattern specification was verified. Reviewed 15 October 2026.

## Observed compositions

| Area | Source specifications | Verified structure/options | Behaviour needing design review |
| --- | --- | --- | --- |
| Actions | [Button](../components/button.md), [Button/Icon](../components/button-icon.md) | Published variants, sizes, icon properties, and state labels | Activation semantics, focus, loading, and action priority rules |
| Forms | [TextField](../components/input.md), [Textarea](../components/textarea.md), [FormHelperText](../components/formhelpertext.md) | Labels/help text, adornments, and named visual states | Validation triggers, error announcements, required-field rules, and submission |
| Dialog composition | [Dialog](../components/dialog.md), [DialogTitle](../components/dialogtitle.md), [DialogActions](../components/dialogactions.md), [Dialog/confirmation](../components/dialog-confirmation.md) | Title/action dependencies, slots, and observed size variants | Opening, focus containment/return, dismissal, confirmation consequences, and persistence |
| Cards | [Card](../components/card.md), [CardHeader](../components/cardheader.md) | Container/data-group options, title options, slots, and header properties | Clickability, selection, action placement policy, and overflow handling |
| Navigation and shell | [Nav](../components/navigation.md), [Nav/Vertical/Item](../components/nav-vertical-item.md), [Nav/Vertical/Subitem](../components/nav-vertical-subitem.md), [Templates](../components/templates.md) | Navigation configurations, active/state labels, child indicators, shell layout variants | Routing, permissions, collapse triggers, keyboard traversal, and history behavior |
| Tables | [Table/Product](../components/table-product.md), [TablePagination](../components/tablepagination.md) | Results visibility, mobile-labelled variants, pagination/scroll dependencies; some table dependencies are external | Sorting/filtering behavior, data loading, selection, paging, and empty/error policies |
| Feedback | [Alert](../components/alert.md), [Snackbar](../components/snackbar.md) | Severity and action/visibility properties | Announcement, timing, dismissal, placement, and recovery rules |
| AI conversation | [Chat/ Conversation](../components/chat-conversation.md) | Original `referrence` and `content` slots; published `Type` options | Streaming, citation verification, retry/cancel, privacy semantics, and retention |
| Voice | [Control/Voice](../components/control-voice.md), [PromptVoice](../components/promptvoice.md) | `Mic`/`Volume`, `Default`/`Muted`, and status labels such as `Connecting`, `Listening`, `Thinking`, and `Speaking` | Recording/permission behavior, transitions, cancellation, transcript access, and recovery |

These are existing component arrangements and configurations, not verified end-to-end interaction rules. Original spellings and property names are preserved. Follow links for actual options and member dimensions; do not assume every combination of options exists.

## Responsive evidence

| Source | Verified configuration | Limit |
| --- | --- | --- |
| [Templates](../components/templates.md) | `Layout=Max Width/Fluid`, `Nav=Open/Collapsed`, `Page=MGMT/Chat` | Member widths are examples, not breakpoints or maximum-content-width definitions |
| [Templates/Mobile](../components/templates-mobile.md) | Separate published mobile component | Does not establish automatic switching or parity with desktop |
| [Table/Product](../components/table-product.md), [CardHeader](../components/cardheader.md), [DatePicker Calendar](../components/datepicker-calendar.md) | `📱 Mobile=False/True` | No breakpoint or reflow policy verified |
| [TablePagination](../components/tablepagination.md) | `On Mobile=False/True` | Example dimensions do not establish a switching threshold |
| [DialogTitle](../components/dialogtitle.md) | Only `📱 Mobile=False` returned | The property label alone does not prove a mobile variant exists |

Raw auto-layout/constraint flags, content-driven resizing, supported viewports, overflow, and responsive transition rules are **Needs design review**. Avoid promoting screenshots or generated rendering classes into layout policy.

## Rules for agents

Use source-backed compositions and exact component properties. Cite the relevant node-backed document when describing an existing pattern. Mark unsupported behavior **Needs design review**; keep a proposed solution separate from verified source facts. Existing external documentation links are references awaiting applicability review, not automatic N1 behavior requirements.

## Missing pattern sources

Provide approved flows or annotated prototypes for forms, dialogs, navigation, tables, AI generation/citations, voice, and feedback. Include triggers, transitions, error/recovery paths, keyboard/focus behavior, responsive rules, scope, owner, and version. Decisions and conflicts follow [design.md](../design.md#source-of-truth); inspection limits are recorded in the [coverage report](../audit/component-documentation-coverage.md).
