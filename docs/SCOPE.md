# MultiClaw — Scope (Lean)

Last Updated: 2026-02-26 (UTC)
Status: Drafting / Discovery

## Collaboration Rules (Mandatory)
- No actions without explicit user approval.
- No suggestions unless explicitly requested.
- Co-build iteratively; requirements may evolve.

## Current Requirements
1. Multi-agent team architecture
2. ML capabilities
3. LLM serving/running with constrained resources (~7.8–8 GB target)
4. Quant market focus:
   - 0DTE options
   - Futures
   - Derivatives
   - Crypto
   - ETFs (including crypto ETFs)
   - Options pricing/greeks (e.g., Black-Scholes)
5. JSON validation/testing with Pydantic
6. JSON-RPC for MCP integration
7. Pytest testing workflows
8. Agentic + LLM benchmark evaluation
9. Observability tooling exploration (including hidden-layer/internal analysis)
10. GraphQL support
11. Postgres support
12. Deployment-grade setup (Tailscale-aware)

## Living / Flexible Scope
- Potential LEAN engine live usage (QuantConnect)
- Free API + MCP-sourced data pathways
- Any modules that may be dropped or split into separate projects

## Scope Policy
- This document is the single source of truth for current and evolving scope.
- Items may move between Current Requirements and Living/Flexible Scope by explicit user direction.
- No architecture or implementation recommendations unless requested.
