# fynnfluegge/agtx

**URL:** https://github.com/fynnfluegge/agtx
**List:** claude-code
**Recommendation:** TBD

## Summary

Terminal-based kanban board for orchestrating spec-driven AI coding agent sessions across multiple projects. Rust. Git worktree + tmux isolation per task. Phases: Backlog → Planning → Running → Review → Done. Supports Claude, Codex, Gemini. Declarative TOML plugin framework, dedicated tmux server, local metadata DB.

## Would / Would Not

**Would:** Rust binary, lightweight multi-project orchestration — kanban visual layer over git worktrees fills a real gap when juggling multiple concurrent feature branches.

**Would not:** tmux dependency limits portability; TOML setup investment before getting value. Overlaps with claude-squad and ccpm.

## Persona Notes

| Persona | Notes |
|---|---|
| AI Researcher | Medium — multi-agent workflow phase management, spec-driven execution patterns. |
| C++ Dev | High — Rust implementation, tmux/process management architecture directly relevant. |
| Python Dev | Low — Rust binary, TOML config, no Python touchpoints. |

## Scores

| Dimension | Score (1-5) |
|---|---|
| Complexity | 3 |
| Time to value | 3 |
| Token efficiency | N/A |
| ServiceNow/AI Foundry fit | 2 |
