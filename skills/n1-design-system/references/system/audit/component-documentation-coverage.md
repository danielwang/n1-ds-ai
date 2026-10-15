# Component documentation coverage

Observed on 15 October 2026 (Australia/Melbourne), through the official Figma MCP server. Figma was not modified.

The published graph contains 492 unique entries: 112 component sets and 380 standalone components. All 492 entries have metadata geometry. There are 804 directly observed member nodes; these are recorded within their parent component files. Nested instances are not counted as standalone components.

## Documentation coverage

| Evidence | Components |
| --- | --- |
| Individual Markdown with twelve sections | 492 |
| Source geometry | 492 |
| Detailed source design sample | 33 |
| Successful node-scoped variable response (may be empty) | 36 |
| Retrieved source-authored description or documentation link | 6 |
| Component-level Code Connect query (including failures) | 34 |

## Page coverage

All 12 graph-referenced page metadata calls succeeded. Ordinary page discovery had previously returned only four pages; that result was not a complete component-library inventory. Three published nodes omitted from their page outline were verified with direct metadata requests.

| Source page | Published entries |
| --- | --- |
| `Cover` | 2 |
| `🥘  nebulaONE.design Docs` | 3 |
| `🍭 Color contrast & blindness` | 2 |
| `🧩  Components` | 126 |
| `🧩 Landmarks` | 19 |
| `🎱  Icons` | 251 |
| `🏙️ AI Brands` | 66 |
| `🏀 Logos` | 3 |
| `🏞️  GRAPHICS` | 3 |
| `👩🏻‍🎓 Personas` | 3 |
| `Branding customisation` | 4 |
| `_Local` | 10 |

## Limits and interpretation

- Published properties, defaults, variant names, and source text samples are preserved without invented runtime APIs.
- Metadata is sparse. Opaque instances, vector internals, unpublished components, and external-library contents are not exhaustively traversed.
- A design sample is one observed member, not verification of all variants' styling or responsive rules.
- Generated rendering classes are labelled observations. Raw auto-layout and constraints require a richer source export.
- Authored descriptions and external documentation links are reproduced where returned. External contents have not been imported as N1 rules.
- State labels do not establish keyboard, focus, dismissal, validation, or navigation behavior. Accessibility compliance has not been inferred.
- Variable responses do not establish full mode coverage, aliases, or property-level bindings.
- Missing or unqueried information is marked **Needs design review**, separately from explicit query failures below.

## Query failures

| Tool | Target | Error evidence |
| --- | --- | --- |
| `get_design_context` | `886:226439` | `You've reached the Figma MCP tool call limit for your Full seat on the Organization plan. Upgrade your seat or plan for more tool calls. Learn more: https://developers.figma.com/docs/figma-mcp-server/rate-limits-access/ ` |

## Distribution validation

This is a retained source audit. The original repository regeneration scripts are not bundled. Run `python3 scripts/validate_package.py` from the skill root for distribution integrity and `python3 scripts/find_component.py QUERY` for discovery. These checks do not establish UI behavior or accessibility compliance.
