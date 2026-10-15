# N1 design-system inventory

Connection update: later verification on 15 October 2026 succeeded. See [token snapshot](../tokens/README.md) for the subsequent page discovery and partial token extraction. The pre-authentication audit record below is historical; a comprehensive component audit has not been completed.

Component documentation update: the published graph subsequently exposed 492 entries across 12 readable pages. See the [current component inventory](component-inventory.md), [index](../components/index.md), and [field-level coverage](component-documentation-coverage.md). Earlier four-page discovery was incomplete; the token snapshot retains its original sampled scope.

Audit date: 15 October 2026 (Australia/Melbourne). Connection check: `2026-10-15T03:21Z`.

**Status: blocked by Figma authentication; source inspection has not started.** This is a coverage record, not a completed design-system audit.

## Source and evidence

| Field | Value | Evidence status |
| --- | --- | --- |
| System | N1 (nebulaONE) | User supplied |
| File key | `01imXcjljmBfqXhqFmv4kz` | Parsed from user-supplied URL |
| Selected node | `915:56433` | Parsed from user-supplied URL; node type and existence not verified |
| Source | [Open selected node](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=915-56433) | User supplied; read access unverified |
| MCP endpoint | `https://mcp.figma.com/mcp` | Verified in `codex mcp list` |
| Server state | Enabled | Verified configuration, not proof of access |
| Authentication | `notLoggedIn` | Codex app-server `mcpServerStatus/list` |
| Advertised tools | Empty list | Same runtime discovery; see [inventory evidence](../docs/setup/mcp-tools.json) |

`python3 scripts/verify_figma.py` stopped before calling `get_metadata`, because the official server returned no callable tools. No design data was read and no Figma writes were attempted. A fresh `codex mcp login figma` flow was initiated; successful completion has not been observed.

## Coverage

| Area | Inspected | Findings |
| --- | --- | --- |
| Selected node | No | Name, type, children, and scope unknown |
| Pages | No | Total and accessible page IDs unknown |
| Sections | No | Structure and section IDs unknown |
| Colours | No | Values, semantic roles, aliases, collections, and modes unknown |
| Typography | No | Families, styles, scales, and usage unknown |
| Spacing | No | Tokens and conventions unknown |
| Radius | No | Values and conventions unknown |
| Effects | No | Shadows, blurs, and styles unknown |
| Layout | No | Auto layout, grids, constraints, and sizing conventions unknown |
| Responsive layouts | No | Examples, breakpoints, and behavior unknown |
| Interaction states | No | State definitions and prototype behavior unknown |
| Descriptions and guidelines | No | Presence, completeness, and external references unknown |

Verified page count: **unknown**. Verified component count: **unknown**. Zero source nodes have been inspected; that does not imply the system contains zero nodes or components.

No individual page has been shown to be inaccessible. The authentication blocker prevents discovering pages at all, so page-level permissions and complete file coverage remain untested.

## Batches to inspect after access is verified

1. Read metadata for the supplied node. Confirm its ID and type in a successful response before extracting design data. Error fallback page lists do not verify the selected node.
2. Discover top-level pages through the server's supported read tools. Record each page ID, source link, accessibility result, and whether it has been fully inspected.
3. Inspect one page or section per batch. Split large responses by child node; record truncation and unvisited branches.
4. Inspect foundations and representative component sets. Record explicit properties and definitions separately from visual observations.
5. Inspect responsive examples, prototype interactions, descriptions, and links to separate documentation. Reconcile counts only when traversal coverage supports them.

These are proposed inspection steps, not findings about N1. Keep the source file read-only.
