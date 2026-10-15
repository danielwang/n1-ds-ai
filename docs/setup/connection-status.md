# Setup status

## Current connection update

On 15 October 2026, subsequent verification returned `oAuth` and the official Figma tool inventory. A successful `get_metadata` response confirmed node `915:56433` as the 🎱 Icons page. File access is verified; read-only token sampling has begun. See [token snapshot](../../tokens/README.md) and [source manifest](../../sources/figma/manifest.json). No full library export is claimed.

The sections below retain the initial setup observations and authentication blocker as historical context; their pending-authentication status has been superseded by this update.

Observed on 15 October 2026 (Australia/Melbourne).

## Environment

The workspace initially contained only `.git/` and `.gitattributes`; the working tree was clean. No existing workspace MCP, VS Code, package, or agent configuration was present. Parent directories had no applicable `AGENTS.md`.

| Check | Result |
| --- | --- |
| Workspace | `/Users/danielwang/Workspace/n1-ds-ai` |
| OS | macOS 26.6.2 |
| Shell | zsh |
| Codex CLI | `0.162.0-alpha.17.2`; version, help, MCP management, and app-server respond |
| Codex location | Bundled with VS Code extension `openai.chatgpt-26.1007.21434-darwin-x64` |
| Codex account | Signed in using ChatGPT |
| VS Code shell launcher | `code` not on PATH; extension installation detected |
| Git | 2.50.1 (Apple Git-155) |
| Node / npm | v20.17.0 / 10.8.2 |
| Python | 3.9.6 |

## Official Figma MCP connection

Added the official server using:

```sh
codex mcp add figma --url https://mcp.figma.com/mcp
```

The server is enabled with Streamable HTTP transport in the existing user config at `~/.codex/config.toml`. No duplicate workspace configuration or manually supplied bearer token was added.

Codex's authenticated runtime inventory reported `notLoggedIn` and zero tools. OAuth was initiated, but completion has not been observed. A successful Codex account login does not establish Figma authentication.

**File access is unverified. The project is not yet ready for extraction.** The original Figma file has not been modified, and no design data has been extracted.

## Finish authentication and verify

Approve the pending Figma OAuth flow in the browser on this Mac. If it has expired, initiate a fresh flow:

```sh
codex mcp login figma
```

Sign in with an account that can open the source file. Keep all credentials and callback responses out of chat and this repository.

Then run from the project root:

```sh
python3 scripts/verify_figma.py
```

The script starts Codex's app-server, not an AI agent turn. It discovers tools through `mcpServerStatus/list`, writes the public tool inventory to `docs/setup/mcp-tools.json`, and calls only `get_metadata` against file `01imXcjljmBfqXhqFmv4kz`, node `915:56433`. It does not read credential files, call write tools, or perform bulk extraction. This environment requires permission to access Codex's user state and the network.

Before marking access verified, inspect the tool response for successful metadata for the requested node. An authentication success, tool listing, error, or fallback page list is insufficient. Record the successful verification date and result here and update `sources/figma/manifest.json` only after that evidence exists.

## Configuration issues

- Figma OAuth completion is the current blocker.
- The current chat has no callable Figma connector tools. CLI access is configured separately; newly configured servers may require reloading the Codex session to appear directly in the IDE chat.
- The sandbox produces a PATH-alias warning and prevents the diagnostic app-server from starting in its restricted mode. Running with approved access reaches the MCP inventory successfully. No CLI reinstall is needed for these checks.
- `code` is unavailable as a shell command; this does not block the bundled Codex CLI.
- ChatGPT, Claude, and other clients have not been configured or authenticated by this Codex setup. Their adapter folders are placeholders.

Sources: [Codex MCP setup](https://learn.chatgpt.com/docs/extend/mcp?surface=cli), [Figma official remote setup](https://developers.figma.com/docs/figma-mcp-server/remote-server-installation/).
