# Visual principles

Status: Figma-derived foundations and repository handling rules. No separately approved N1 visual/brand rulebook was found. Reviewed 15 October 2026.

## Verified foundation references

| Foundation | Available evidence | Interpretation limit |
| --- | --- | --- |
| Colour | [45 named observed values](../tokens/colors.json), with source hex values and provenance | Semantic roles, permissible pairings, contrast compliance, and theme mappings are not established by names |
| Typography | [Raw shared definitions](../tokens/typography.json); component-scoped style observations in [Button](../components/button.md) and [TextField](../components/input.md) | The shared snapshot includes Chakra Petch and Segoe UI observations; these do not establish an approved global font hierarchy, fallback stack, or scale |
| Spacing | [10 discovered names](../tokens/spacing.json) in `[Core] Spacing` | Values were not exposed by that shared snapshot; suffixes do not define dimensions |
| Sizing | [Coverage record](../tokens/sizing.json) and individual component/member geometry | Example bounds do not establish a sizing scale, minimum targets, or responsive rules |
| Radius | [Radius evidence](../tokens/radius.json): one raw value and 10 discovered names | Units and complete definitions remain unverified |
| Borders | [Four discovered border-colour variables](../tokens/borders.json) in `[Themes]` | Colour names do not establish width, style, or a composite border specification |
| Shadows/effects | [12 discovered shadow styles](../tokens/effects.json) | Parameters and elevation usage rules were not exported |
| Opacity | [Coverage record](../tokens/opacity.json); alpha-bearing colours in colour data | Colour alpha is not proof of a standalone opacity token |
| Icons and assets | Original names, source links, and bounds in the [component index](../components/index.md) | Semantic meaning, accessibility treatment, and approved substitution rules are not established for every asset |
| Layout | [Templates](../components/templates.md), [Nav](../components/navigation.md), and component variants | Generated rendering classes do not expose all raw auto-layout flags or constraints |

## Repository rules for using this evidence

- Match the exact source component, variant, and context before reusing an observed value. Preserve token names, including punctuation and commas.
- Use recorded definitions where they cover the design. Missing values, units, aliases, and modes remain **Needs design review**; do not fill them with an assumed scale.
- Keep product styling separate from documentation artwork. `_docs/*`, `_methodology/*`, and the `Design Principle` presentation card do not establish product-wide fonts, gradients, or spacing.
- Component-set canvas bounds describe the arranged set. Use the actual member dimensions for the source example; neither implies automatic sizing behavior.
- Record visual recommendations as proposed until supported by an applicable source or explicit approval.

These handling rules preserve evidence; they do not add brand rules. Read the [token snapshot limitations](../tokens/README.md) and [component coverage report](../audit/component-documentation-coverage.md) before implementation.

## Missing sources

**Needs design review:** approved colour roles and theme specifications; typography hierarchy and units; spacing/sizing scales; radius and elevation roles; icon/illustration guidelines; motion requirements; grid, density, breakpoint, and overflow rules; and complete variable collections with mode-specific aliases. Resolve conflicts through [design.md](../design.md#source-of-truth).
