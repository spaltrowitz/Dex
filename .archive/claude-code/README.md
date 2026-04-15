# Archived Claude Code Artifacts

These files were part of the original Claude Code integration for Dex.
They have been archived as part of the Copilot CLI refactor.

The Copilot CLI equivalents are:
- `.github/agents/dex.agent.md` — main agent file (replaces CLAUDE.md)
- `.copilot/mcp-config.json` — MCP server config (replaces .mcp.json)
- `.copilot/skills/` — skill definitions (replaces .claude/skills/)

## What was archived
- `CLAUDE.md` — the original system prompt / brain
- `.claude/` — settings, hooks, skills, flows, guides, plugins, reference
- `.claude-plugin/` — Claude plugin packaging
- `System/claude-code-state.json` — Claude session state

## What was kept
- `core/mcp/` — vault-native MCP servers (agent-agnostic Python code)
- `System/` — user config (pillars.yaml, user-profile.yaml)
- All vault content (projects, areas, resources, tasks, etc.)

