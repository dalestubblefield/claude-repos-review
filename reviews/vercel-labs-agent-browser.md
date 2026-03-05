# vercel-labs/agent-browser

**URL:** https://github.com/vercel-labs/agent-browser
**List:** claude-code
**Recommendation:** TBD

## Summary

Headless browser automation CLI for AI agents. Rust native binary (sub-millisecond overhead) with Node.js/TypeScript fallback. Chromium-based, accessibility tree snapshots, semantic locators (ARIA roles, text matching), network interception, screenshot comparison, tracing/profiling.

## Would / Would Not

**Would:** Already installed and in use (`/opt/homebrew/bin/agent-browser`) — confirmed active in workflow. Rust binary performance makes it ideal for agent-driven web automation.

**Would not:** Nothing significant — already part of the toolkit.

## Persona Notes

| Persona | Notes |
|---|---|
| AI Researcher | Medium — accessibility tree as agent perception layer is an interesting design pattern. |
| C++ Dev | High — Rust native binary architecture, performance-critical design decisions. |
| Python Dev | Medium — Node.js fallback, Python agents can orchestrate via CLI subprocess. |

## Scores

| Dimension | Score (1-5) |
|---|---|
| Complexity | 2 |
| Time to value | 5 |
| Token efficiency | 4 |
| ServiceNow/AI Foundry fit | 4 |
