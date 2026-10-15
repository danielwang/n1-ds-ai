# N1 token snapshot

Extracted on 15 October 2026 through the official Figma MCP server at `https://mcp.figma.com/mcp`. **This is a partial, evidence-backed snapshot, not a complete library export.** The original Figma file was not modified.

Source file: `01imXcjljmBfqXhqFmv4kz`. The supplied node [`915:56433`](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=915-56433) was verified as the **🎱 Icons** page before extraction. Authentication now succeeds (`oAuth`); earlier audit files describe the previous unauthenticated attempt.

Later component inspection discovered 12 readable pages through the published component graph, compared with the four returned by the original page-discovery call. The token scope below remains the earlier sample; it is not a complete inventory of those 12 pages. See [component coverage](../audit/component-documentation-coverage.md).

## Files and verified coverage

| File | Value-bearing definitions observed | Additional library metadata |
| --- | --- | --- |
| [colors.json](colors.json) | 45 named colour values, normalized as DTCG colour tokens | No additional results from the scoped `colour` query |
| [typography.json](typography.json) | 2 raw font definitions with parsed attributes | No additional results from the scoped `typography` query |
| [spacing.json](spacing.json) | None exposed in sampled nodes | 10 FLOAT variable names and keys in `[Core] Spacing`; values unavailable |
| [sizing.json](sizing.json) | None exposed | No results from the scoped query |
| [radius.json](radius.json) | `radius-1` returned as the string `8`; unit not exposed | 10 FLOAT variable names and keys in `[Core] Radius`, including `radius-1` |
| [effects.json](effects.json) | None exposed | 12 EFFECT style names and keys; parameters unavailable |
| [borders.json](borders.json) | None exposed | 4 COLOR variables in `[Themes]`; values unavailable |
| [opacity.json](opacity.json) | No standalone opacity definition exposed | No results from the scoped query |
| [other.json](other.json) | No additional categories exposed | Coverage unknown |

Counts are counts of distinct names observed or discovered in these calls, not total library counts. Radius discovery overlaps the one value-bearing observation. An empty result does not prove a category is absent. Border variables are colours; no border width/style or composite border definition was retrieved. `grey/8%` has a returned alpha-bearing colour, not a verified standalone opacity token.

## JSON structure and interpretation

All nine files are JSON objects with the same metadata envelope at `$extensions["design.nebulaone.figma"]`. This namespace is repository metadata, not a Figma collection name. The metadata includes scope, completeness, counts, unknown fields, `discoveredDefinitions`, `unconvertedDefinitions`, and conflicts.

The colour records use the [DTCG 2025.10 format](https://www.designtokens.org/tr/2025.10/format/): original names remain literal keys, `$type` is `color`, and `$value` contains sRGB components and alpha. Original hex spelling, source file/node IDs, links, observation timestamps, tool, and raw-response paths are retained per record. Hex alpha is converted directly from its byte value; for example, `#919eab14` retains alpha `20/255`, without rounding to an assumed percentage.

Typography and radius records remain in `unconvertedDefinitions` with exact returned strings, parsed numbers where available, and explicit unknown units. They are not emitted as synthetic DTCG tokens with guessed units or line-height semantics. The other files contain metadata-only discoveries or explicit coverage limitations. A token consumer that ignores extensions will therefore see 45 colour tokens and no tokens in the other files. Do not interpret the empty token groups as complete empty libraries.

No `$schema` is claimed for the complete snapshot. Validation checks the supported colour-token subset and provenance; it does not certify full DTCG conformance or source completeness.

## Names, collections, modes, and aliases

- Names are unchanged, including slashes, spaces, punctuation, and commas such as `spacing-0,5`. Slashes have not been converted into an assumed group hierarchy.
- Search discoveries retain `key`, `variableSetKey`, `variableCollectionName`, `variableType` or `styleType`, `libraryKey`, scopes, and `filePath` exactly as returned. A search path is not treated as a local file or a Figma node ID.
- Node definition responses did not expose variable IDs, collection IDs, alias targets, mode names, mode IDs, or `valuesByMode`. Those fields are unknown (`null` or `not-exposed`), rather than fabricated.
- `[Core] Spacing`, `[Core] Radius`, and `[Themes]` are confirmed collection names from search. The colour observations cannot be assigned to those collections solely by name. The `radius-1` observation has the same name as a library discovery, but its variable identity is not confirmed by an ID.
- Names such as `primary/main`, `text/primary`, `System/Grey/cf-color-black`, and `grey/900` are preserved. Primitive/semantic classification is `unknown`; prefixes may suggest roles but do not verify them.
- Equal observed values remain separate named records. In particular, `primary/darker` and `grey/900` both returned `#161c24`; that does not prove either aliases the other.
- No aliases have been intentionally flattened by these scripts. The MCP responses already provide name/value maps without alias metadata. The source alias graph is unrecoverable from those maps and remains unknown. No light/dark modes have been inferred from names containing `light` or `dark`.
- A node's observed value is not guaranteed to be its canonical variable default. The source might be a style or a variable, and the active mode is not identified by this response.

## Typography observations

| Original name | Family | Style / weight | Size | Line height | Letter spacing |
| --- | --- | --- | --- | --- | --- |
| `Body-Small` | Chakra Petch | Regular / 400 | 14 | 20 | 0.3499999940395355 |
| `desktop/subtitle1` | Segoe UI | Semibold / 600 | 16 | 24 | 0 |

The numeric fields above are verbatim observations; their units were not included in the tool strings. No family fallback, line-height ratio, or responsive typography relationship has been added.

## Metadata-only discoveries

- Spacing: `spacing-0,5`, `spacing-0,75`, `spacing-1`, `spacing-1,5`, `spacing-2`, `spacing-3`, `spacing-4`, `spacing-5`, `spacing-6`, `spacing-7`.
- Radius: `radius-0,5`, `radius-0,75`, `radius-1`, `radius-1,25`, `radius-1,5`, `radius-1,75`, `radius-2`, `radius-3`, `radius-4`, `radius-50%`. A numeric suffix or `%` in a name does not establish its value or unit.
- Effects: `shadow/z1`, `shadow/z4`, `shadow/z8`, `shadow/z12`, `shadow/z16`, `shadow/z20`, `shadow/z24`, `shadow/card`, `shadow/dialog`, `shadow/dropdown`, `shadow/drawer-left`, `shadow/drawer-right`.
- Borders: `border/border-light`, `border/border`, `border/border-dark`, `border/border-black`.

These names are discoveries, not usable value definitions. Search results may be ranked or limited, and they do not establish collection totals.

## Inspection scope and limitations

Top-level page discovery returned four pages:

| Page | Node | Coverage |
| --- | --- | --- |
| Cover | [45:58183](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=45-58183) | Metadata; thumbnail variable sample |
| 🎱 Icons | [915:56433](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=915-56433) | Metadata; one icon and three sections sampled |
| 🏞️ GRAPHICS | [2944:1766810](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=2944-1766810) | Metadata; logos, background, graphics section, and an illustration sampled |
| _Local | [67:137263](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=67-137263) | Metadata; documentation templates, swatch, and local asset samples |

There were 19 `get_variable_defs` calls: 15 returned definitions, 3 returned empty maps, and the page-level call on `915:56433` returned a selection error. Concrete child-node calls succeeded, so no user selection change was needed. This is sampled coverage, not an exhaustive traversal of every node, variable, style, or referenced library.

Library discovery returned Solar Icons, 📖 nebulaONE.design, and Design annotation kit as subscribed libraries. The token-category search was restricted to the discovered nebulaONE library key to avoid importing unrelated library tokens. Available-but-unsubscribed libraries were not imported. The full nebulaONE key and search inputs are retained in evidence.

All four page metadata requests succeeded. No page-level permission error was observed. Variable coverage remains incomplete even though page structure is readable. MCP resource discovery exposed guidance/code resources, not a complete variable export resource.

## What requires a fuller Figma export

The observed `get_variable_defs` and search responses cannot provide a complete alias- and mode-preserving export. The [Figma Variables API](https://developers.figma.com/docs/rest-api/variables-endpoints/) documents the read endpoint:

```text
GET /v1/files/01imXcjljmBfqXhqFmv4kz/variables/local
```

It supplies variable and collection objects, IDs, `valuesByMode`, alias objects, modes, and defaults, including local variables and remote variables used in the file. It requires `file_variables:read` and is documented as available to full members of Enterprise organizations. Eligibility and separate REST authentication have not been verified here. MCP OAuth should not be assumed to grant REST access.

The published-variable endpoint can help reconcile published identities, but omits modes. Referenced library definitions may require access to their originating files. Preserve collection IDs and mode IDs independently, retain alias targets as references, and flag unresolved external targets; do not infer semantic classification from the alias graph alone.

Typography styles, effect parameters, borders, and node bindings also require [file/node data](https://developers.figma.com/docs/rest-api/file-endpoints/) where values are represented in document nodes. Read access uses `file_content:read`. A style-name listing does not supply every style's values, and unused/unrepresented styles may require an authorized read-only Plugin API export. No REST API or plugin export was performed in this task.

## Evidence, regeneration, and validation

Raw MCP responses and request arguments are retained under [`sources/figma/token-evidence/`](../sources/figma/token-evidence/). The [coverage manifest](../sources/figma/token-evidence/coverage.json) records every variable-definition target and outcome. Credentials are not included.

To rebuild and validate the existing offline snapshot:

```sh
python3 scripts/build_tokens.py
python3 scripts/validate_tokens.py
```

Validation checks all nine token JSON files and retained evidence JSON for parse errors, duplicate keys, and non-finite constants. It verifies colour shape/ranges, round-trips colours to the exact source hex values, checks original names and provenance, reconciles counts, and verifies metadata discoveries against search results. It does not verify missing modes/aliases, full library coverage, or unexposed values.

Recommended next extraction priority: obtain complete variable/collection data; reconcile identifiers and mode-specific aliases; obtain typography/effect style definitions with explicit units; then emit normalized dimension/composite tokens and per-mode outputs. Preserve this snapshot as evidence until those definitions are verified.
