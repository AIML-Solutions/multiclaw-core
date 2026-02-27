# MultiClaw Core

**MultiClaw Core** is the governance and architecture hub for AIML Solutions’ multi-agent platform.

It defines how specialized agent teams coordinate across quant research, market data engineering, web3 analytics, model benchmarking, and product delivery.

## Why this repository exists

Most agent projects fail because they mix strategy, execution, and infrastructure in one place.
MultiClaw Core separates concerns:

- architecture and operating model
- department-level boundaries and permissions
- model routing and cost controls
- rollout governance and reporting standards

## Active ecosystem

- `multiclaw-core` (this repo)
- `multiclaw-quant`
- `multiclaw-mlflow`
- `multiclaw-blockchain`
- `multiclaw-llm`
- `multiclaw-frontend`
- `multiclaw-public-library`

## Core documents

- [`docs/SCOPE.md`](docs/SCOPE.md) — strategic scope and principles
- [`docs/REPO_TOPOLOGY.md`](docs/REPO_TOPOLOGY.md) — repository segmentation model
- [`docs/AGENT_MODEL_ROUTING.md`](docs/AGENT_MODEL_ROUTING.md) — role-based model defaults/fallbacks
- [`docs/LEAN_SETUP.md`](docs/LEAN_SETUP.md) — LEAN-related operating notes
- [`docs/README.md`](docs/README.md) — docs entrypoint

## Current focus

1. Keep architecture coherent while repos scale independently.
2. Enforce cost-aware model routing and benchmark-led promotion.
3. Maintain professional reporting for stakeholder transparency.
4. Provide a safe operating baseline for public-facing launch.

## Reporting

Narrated briefs and raw snapshots are maintained under [`reports/`](reports/).

## Contributing

1. Open an issue or draft proposal in this repo.
2. Keep changes scoped to architecture/governance concerns.
3. Avoid leaking credentials or environment-specific secrets.
4. Prefer small, reviewable PRs with explicit rationale.

## License

MIT — see [LICENSE](LICENSE).
