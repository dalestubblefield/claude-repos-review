# cortex-tms/cortex-tms

**URL:** https://github.com/cortex-tms/cortex-tms
**List:** claude-code
**Recommendation:** TBD

## Summary

Documentation governance system keeping AI coding agents aligned with project standards over time. Git-based staleness detection, HOT/WARM/COLD doc tiering, 316 tests at 97% pass rate, GitHub Actions CI integration. TypeScript/Node.js CLI.

## Would / Would Not

**Would:** Solves real documentation drift for multi-developer AI-assisted teams. Git-based staleness detection + CI is low-friction and compatible with branch+PR workflow.

**Would not:** Single-developer projects don't suffer the multi-agent consistency problem this solves.

## Persona Notes

| Persona | Notes |
|---|---|
| AI Researcher | High — HOT/WARM/COLD tiering mirrors cache eviction applied to knowledge management; doc-agent alignment is novel. |
| C++ Dev | Low — Node.js only, no C++ touchpoints. |
| Python Dev | Low — TypeScript-only implementation. |

## Scores

| Dimension | Score (1-5) |
|---|---|
| Complexity | 3 |
| Time to value | 4 |
| Token efficiency | N/A |
| ServiceNow/AI Foundry fit | 3 |
