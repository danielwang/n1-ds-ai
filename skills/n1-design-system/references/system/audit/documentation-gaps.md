# N1 documentation gaps and extraction priorities

Connection update: later Figma authentication succeeded and partial token sampling was completed; see [token snapshot](../tokens/README.md). The authentication blockers below describe the earlier attempt, not the current connection. Comprehensive documentation coverage remains unverified.

Component documentation update: structural documentation now covers 492 published entries. The [coverage report](component-documentation-coverage.md) records deeper inspection coverage and the actual Figma tool-call limit that stopped further queries. Remaining review gaps include raw layout flags, behavior, accessibility, modes/aliases, and uninspected source descriptions.

Audit date: 15 October 2026 (Australia/Melbourne).

**Status: audit incomplete; authentication prevents source inspection.** No design-system defect or missing guideline has been verified.

## Verified blockers and evidence gaps

| Finding | Evidence | Impact |
| --- | --- | --- |
| Official Figma server is configured but unauthenticated | `mcpServerStatus/list`: `notLoggedIn`, empty tools list | Selected-node and page inspection cannot begin |
| File access has not been verified | Verification stopped before `get_metadata` | Extraction gate remains closed |
| Design documentation coverage is unknown | No descriptions, canvas text, or external links inspected | Cannot classify components as documented or undocumented |
| Page coverage is unknown | Page discovery has not run | Cannot identify page-specific permission failures or claim complete coverage |

The missing evidence is a limitation of this audit. It is not evidence that N1 lacks tokens, variants, accessibility guidance, responsive layouts, or documentation.

## Questions to resolve through inspection

- Are raw values, semantic aliases, modes, and component tokens explicitly defined and consistently linked?
- Which typography, spacing, radius, effects, and layout conventions have written guidance?
- Which component sets expose explicit variants and properties, and which states are documented?
- Do responsive examples include explicit behavior and breakpoint rules?
- Do component descriptions explain intended use, restrictions, content, interactions, and accessibility?
- Are duplicate names, detached examples, legacy sections, or conflicting definitions present?

These are audit questions, not findings. Visual repetition may suggest a convention; it must remain an observation unless definitions or written guidance confirm it.

## Documentation to import separately

No external documentation sources have been discovered or verified. After access is restored, inspect descriptions, canvas annotations, and links for companion material such as usage guidance, accessibility specifications, content standards, code examples, governance, or release history. These are candidate categories only; their existence is not established.

For each discovered source, record its exact URL, linked Figma node, owner/version if stated, access outcome, and intended import scope. Keep unavailable sources on a separate follow-up list. Do not infer external-document content from link labels.

## Recommended extraction priorities

| Priority | Action | Why |
| --- | --- | --- |
| P0 | Complete OAuth and verify the supplied node through an official read tool | Establishes actual source access |
| P1 | Map pages and sections, with IDs and access/truncation status | Establishes audit scope and supports defensible counts |
| P2 | Inspect foundations, aliases, modes, and provenance | Establishes shared values before component specifications |
| P3 | Inventory component sets, main components, variants, and properties | Establishes reusable component structure without counting instances as definitions |
| P4 | Inspect descriptions, interaction states, responsive examples, and accessibility guidance | Separates explicit rules from visual examples |
| P5 | Import discovered companion documentation and reconcile conflicts | Fills evidenced gaps while preserving source attribution |

The order is an architectural recommendation, not a source-derived N1 rule. Reprioritize after discovering actual library structure and usage evidence.

## Completion criteria

An audit can be reported as complete only for an explicit inspected scope: list every discovered page and section with coverage status; reconcile component counts; attach source links to findings; distinguish confirmed definitions, visual observations, assumptions, and unresolved questions; and report inaccessible or truncated branches. No changes to Figma are required.
