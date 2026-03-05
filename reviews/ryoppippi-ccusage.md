# ryoppippi/ccusage

**URL:** https://github.com/ryoppippi/ccusage
**List:** claude-code
**Recommendation:** TBD

## Summary

CLI tool analyzing Claude Code token usage and costs from local JSONL files. TypeScript (99.2%), pnpm, Nix flakes. Daily/monthly/session views, per-model cost breakdowns, JSON export, MCP server integration. Monorepo also covers OpenAI Codex, OpenCode, Pi-agent, Amp. Offline pricing, ultra-lightweight bundle.

## Would / Would Not

**Would:** Lightweight, local-first cost visibility with no external dependencies — ideal for tracking API spend without another SaaS tool.

**Would not:** Nix-based dev environment adds friction if not already in that ecosystem.

## Persona Notes

| Persona | Notes |
|---|---|
| AI Researcher | Medium — multi-model usage analytics could inform model routing decisions. |
| C++ Dev | Low — TypeScript only. |
| Python Dev | Low — TypeScript only. |

## Scores

| Dimension | Score (1-5) |
|---|---|
| Complexity | 2 |
| Time to value | 5 |
| Token efficiency | N/A (measures it) |
| ServiceNow/AI Foundry fit | 2 |
