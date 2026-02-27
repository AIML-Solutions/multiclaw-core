# MultiClaw Meeting Minutes Protocol

Purpose: maintain durable, formal records after major work sessions.

## When to produce minutes
Create minutes whenever one or more of these occurs:
- multiple repositories changed
- infrastructure/services reconfigured
- deployment or visibility changes (private/public)
- website redesign or external-facing updates
- major roadmap or architecture decisions

## Required output files
For each major session date (`YYYY-MM-DD`):
- `reports/YYYY-MM-DD/MEETING-MINUTES-<topic>.md`
- optional `reports/YYYY-MM-DD/<topic>.raw.log` for raw evidence

## Required sections
1. Session metadata (date/time, participants)
2. Objectives
3. Work completed (itemized)
4. Decisions made
5. Risks / blockers
6. Follow-up actions (owner + due target)
7. Validation evidence (deploy links, workflow runs, URLs)

## Naming conventions
- Use professional display names in prose: `MultiClaw-Core`, `MultiClaw-Quant-Tools`, etc.
- Keep URL slugs as actual repo paths.

## Cadence
- Write minutes immediately after large execution blocks.
- Keep minutes concise, factual, and decision-oriented.

## Quality bar
- No secrets.
- Link to verifiable artifacts.
- Prefer explicit outcomes over vague summaries.
