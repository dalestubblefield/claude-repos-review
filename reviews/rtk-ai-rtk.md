# rtk-ai/rtk

**URL:** https://github.com/rtk-ai/rtk
**List:** claude-code
**Recommendation:** TBD

## Summary

CLI proxy intercepting and compressing command outputs before they reach Claude Code, reducing token consumption 60-90%. Rust single binary, zero dependencies. Hook-based integration transparently rewrites commands (git, file reads, test runs, linters). Parsers for Python, Go, JavaScript, Kubernetes, Docker. Savings analytics built-in.

## Would / Would Not

**Would:** Already installed and confirmed active in workflow — 60-90% token savings on dev operations is validated and measurable.

**Would not:** Nothing significant — already in the toolkit.

## Persona Notes

| Persona | Notes |
|---|---|
| AI Researcher | Medium — token compression as LLM I/O optimization, hook-based transparent interception patterns. |
| C++ Dev | High — Rust implementation, zero-dependency binary, output parser architecture. |
| Python Dev | High — Python output parser included, directly reduces Python test/lint token cost. |

## Scores

| Dimension | Score (1-5) |
|---|---|
| Complexity | 1 |
| Time to value | 5 |
| Token efficiency | 5 |
| ServiceNow/AI Foundry fit | 4 |
