# MultiClaw LEAN Instance (Local Docker)

Path: `/home/aimls-dtd/.openclaw/workspace/projects/MultiClaw/lean`

## What is set up
- Docker image pulled: `quantconnect/lean:latest`
- Compose service: `multiclaw-lean`
- Mounted folders:
  - `lean/data` -> `/Lean/Data`
  - `lean/results` -> `/Lean/Results`
  - `lean/config` -> `/Lean/Config`

## Validate the instance
```bash
cd /home/aimls-dtd/.openclaw/workspace/projects/MultiClaw/lean
docker compose run --rm lean --help
```

## Notes
- This is infrastructure setup only.
- No brokerage, data-provider, or live-trading credentials were added.
- No strategy jobs were started.
