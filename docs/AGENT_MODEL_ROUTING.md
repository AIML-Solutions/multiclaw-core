# MultiClaw Agent Model Routing (Cost/Speed First)

## Principles
1. Smallest model that can reliably do the task.
2. Automatic escalation only on failure/low-confidence.
3. Hard per-task budget caps by agent role.

## Default policy
- Primary (standard): `openai/gpt-5.1-codex`
- Deep fallback: `openai-codex/gpt-5.3-codex`
- Routine backup: `HF-Mistral-Backup` (`mistralai/Mistral-Nemo-Instruct-2407`) via Perplexica/OpenAI-compatible endpoint

Central routing contract: `operations/model-routing-policy.yaml` (workspace-relative).

## Team roles (initial)
- quant-researcher
- market-data-engineer
- chain-analyst
- dashboard-builder
- doc-librarian

## Escalation triggers
- schema validation failure
- regression test failure
- unresolved exception after 2 retries
- confidence below configured threshold

## Cost controls
- chunk large tasks into scoped subtasks
- cap max tokens/context per role
- log cost per task into daily report

## Operational notes
Model aliasing and defaults should be revisited weekly using benchmark output from LLM Department (`terminal-bench`, `harbor`).
