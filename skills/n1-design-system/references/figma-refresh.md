# Refresh from official Figma MCP

Read only when a task needs details newer than, or absent from, the bundled snapshot.

Official endpoint: `https://mcp.figma.com/mcp`. Source file key: `01imXcjljmBfqXhqFmv4kz`. Initial supplied node: `915:56433` (Icons). This page is not the whole library. Resolve component nodes through the bundled index or current discovery.

Use the client's available official Figma tools; do not assume a particular host, CLI, tool namespace, or authenticated account. This skill does not install an integration or contain credentials. If access is unavailable, work from the dated snapshot where sufficient and identify the fresh evidence still needed. Authentication/permission flows stay in the client's supported UI; never request credentials in chat.

1. Verify authenticated read access to the intended file and node. An enabled endpoint or successful account identity alone is insufficient. Before any new extraction, also verify the initial source node required by the [source workspace rules](system/AGENTS.md).
2. Use `get_metadata` for structural discovery and `list_file_components_for_code_connect` for published identities/properties where available. Earlier ordinary page discovery returned only four pages, while the published graph exposed 12 readable page references; reconcile discovery methods before claiming completeness.
3. Use `get_variable_defs` on concrete component/member nodes. It can return observed name/value maps without aliases, modes, collections, or units. Do not describe that as a complete token export. Use `get_code_connect_map` for actual mapped implementation references.
4. For richer visual evidence, use `get_design_context` when available and follow any prerequisite guidance exposed by that tool. Its generated code is not a verified implementation API. Raw node/variable data may require an authorized API export; do not fabricate it when unavailable.
5. Inspect manageable batches. Retain file key, node IDs, tool, observation date, mode/context if exposed, and coverage/failures. Stop further requests on a tool-call quota or rate-limit response; do not repeatedly retry. The retained snapshot includes a previous quota failure, which is not proof of the current account state.

Keep Figma read-only. Do not invoke create/edit/delete/upload or Code Connect mutation tools, and do not use general-purpose write-capable tools to change the source. Fresh evidence does not silently supersede a different approved policy or mode: follow the [conflict-resolution process](system/design.md#source-of-truth).

Refreshing evidence for a task does not authorize publishing, deployment, modifying a library, or replacing shared guidance. Offline generation and review remain available within the snapshot's stated limits.
