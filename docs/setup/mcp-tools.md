# Figma MCP tool inventory

## Runtime availability

The initial Codex app-server discovery returned `authStatus: notLoggedIn` and an empty tool list. **No Figma tools are currently verified as callable.** See `mcp-tools.json` for that observed result. Rerun `scripts/verify_figma.py` after OAuth to replace the inventory with actual server-advertised tool schemas.

## Documented capabilities (not yet verified for this connection)

The [official Figma tool reference](https://developers.figma.com/docs/figma-mcp-server/tools-and-prompts/) documents the following relevant capabilities. Availability varies; runtime discovery is authoritative.

| Tool | Capability |
| --- | --- |
| `whoami` | Account and plan details |
| `get_metadata` | Node structure outline |
| `get_design_context` | Design implementation context |
| `get_screenshot` | Visual reference |
| `get_variable_defs` | Selection variables and styles |
| `download_assets` | Asset exports |
| `get_libraries` | Library discovery |
| `search_design_system` | Library search |
| `get_code_connect_map` | Existing code mappings |
| `get_motion_context` | Animation context |
| `get_figjam` | Diagram context |

The server also documents generative-plugin and shader readers, Code Connect suggestion tools, and write capabilities. Write tools include `use_figma`, `generate_figma_design`, `create_new_file`, `upload_assets`, `generate_diagram`, and Code Connect mutation tools. These are outside this project's read-only workflow and must not be invoked on the source. `create_design_system_rules` is documented as an MCP prompt, not a design-token export tool.

Selection context does not establish a complete design-system export. During later extraction, verify coverage, aliases, modes, library scope, variants, and provenance explicitly.
