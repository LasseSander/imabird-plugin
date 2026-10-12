# IMABIRD plugin

Edit short-form videos in [IMABIRD](https://www.imabird.productions) from Claude Code, Codex or ChatGPT. The plugin connects your agent to the IMABIRD Agent MCP and adds a skill for editing Cuts.

## API key

Create a key with **Agent MCP** access at https://www.imabird.productions/api. The key is shown once.

## Claude Code

```bash
claude plugin marketplace add LasseSander/imabird-plugin
claude plugin install imabird@imabird
```

Enter the key when asked, or later with `/plugin configure imabird@imabird`.

## Codex

```bash
codex plugin marketplace add LasseSander/imabird-plugin
```

Install **IMABIRD** from the Plugins directory and enter the key in its connection setup.

## Contents

- `.mcp.json`, `mcp.json`: the IMABIRD Agent MCP at `https://www.imabird.productions/agent/mcp`
- `skills/imabird/SKILL.md`: how to edit a Cut through it
- `.claude-plugin/`: Claude Code manifest and marketplace
- `plugin.json`, `.agents/plugins/marketplace.json`: Codex and ChatGPT manifest and marketplace
