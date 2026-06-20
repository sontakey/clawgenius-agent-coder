# clawgenius-agent-coder

Production software engineering and DevOps agent.

## Install

```bash
hermes profile install github.com/sontakey/clawgenius-agent-coder --alias --name coder
```

## Update

```bash
hermes profile update coder
```

## What ships

- `SOUL.md` — profile persona and operating contract
- `skills/` — bundled ClawGenius operating skills
- `mcp.json` — MCP placeholder, intentionally empty until integrations are picked
- `cron/` — cron placeholder, intentionally empty by default
- `distribution.yaml` — manifest and update ownership

## What never ships

No credentials, memories, sessions, logs, workspaces, or local user customization.

## Recommended toolsets

`terminal, file, search, session_search, skills, todo`

Configure locally after install with:

```bash
hermes -p coder tools
hermes -p coder model
```
