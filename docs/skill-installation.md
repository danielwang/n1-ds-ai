# Install and use the N1 skill

The canonical skill is [skills/n1-design-system](../skills/n1-design-system/SKILL.md). It bundles its references and Python helpers; the original repository and live Figma access are not runtime dependencies. Packaging does not configure or authenticate an MCP server.

## Build and verify

From the repository root:

```sh
python3 scripts/validate_repository.py
python3 scripts/package_n1_skill.py --zip
```

This creates ignored local `skill.zip` and `skill.zip.sha256`. Keep both together when sharing an approved distribution. The archive contains one `n1-design-system/` directory. Validate a received archive by comparing its SHA-256 with the separately trusted checksum, extracting into a fresh directory, and running `python3 scripts/validate_package.py` from the extracted skill root. A checksum establishes integrity, not trust or permission to redistribute.

## Codex local discovery

In a consuming project, create `.agents/skills/` and copy the complete `n1-design-system/` folder into it, or extract the reviewed ZIP there. The result must be `.agents/skills/n1-design-system/SKILL.md`. Avoid duplicate installations with the same name. For personal use across projects, the documented user location is `~/.agents/skills/`; installing outside the workspace is a separate local action.

Invoke explicitly: `Use $n1-design-system to review this interface. Read the relevant components and token references, and report unsupported assumptions.` For generation, provide the actual frontend repository and implementation package; this documentation repository supplies no component runtime. Codex discovers skills in these locations; restart if an update is not detected. See [official skill documentation](https://learn.chatgpt.com/docs/build-skills).

The source skill lives under `skills/` for maintenance, so merely opening this repository does not install it into Codex's `.agents/skills` discovery path. Installation is not performed by CI. Current OpenAI guidance recommends plugins for broader distribution; this repository provides a portable skill directory and ZIP, not a published plugin.

## Other compatible clients

Use a client's documented Agent Skills directory/import mechanism and preserve the entire folder. `agents/openai.yaml` supplies OpenAI presentation metadata; it is not a universal installer. If a client supports reference reading but not scripts, consult the bundled Markdown component index and JSON directly. Verify that the client actually discovers and invokes the skill before relying on it. ChatGPT, Claude and other hosts have not been installation-tested here; no universal ZIP-upload flow is assumed.

For current visual details, connect the official Figma MCP server in that client and verify file access before extraction. Authentication is client-specific and is never included in the package. Follow the [read-only refresh reference](../skills/n1-design-system/references/figma-refresh.md).

## Upgrade and smoke test

Replace an installed skill only after reviewing the new source diff, approval labels and checksum. Validate the fresh directory before removing the prior installation. Ask the agent to find a documented Button variant and explain token/mode coverage limits. Run `scripts/find_component.py Button` and `scripts/check_selection.py --help` from the skill root for helper usage. Review its decisions against source evidence; package validation alone cannot validate rendered UI or WCAG compliance.
