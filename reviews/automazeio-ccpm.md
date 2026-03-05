# automazeio/ccpm

**URL:** https://github.com/automazeio/ccpm
**List:** claude-code
**Recommendation:** TBD

## Summary

Project management system for spec-driven development using GitHub Issues as coordination layer. Markdown + shell scripts. Transforms PRDs into epics, parallelizes task execution across AI agents via GitHub Issues. Git worktrees for conflict prevention. Full audit trail visible to distributed teams.

## Would / Would Not

**Would:** GitHub Issues as coordination layer is elegant — no new tooling, full team visibility, audit trail built-in. PRD → epic → parallel tasks aligns perfectly with existing branch+PR+issue workflow.

**Would not:** Shell script + Markdown implementation may be fragile at scale.

## Persona Notes

| Persona | Notes |
|---|---|
| AI Researcher | High — GitHub Issues as multi-agent coordination substrate is an interesting architectural pattern. |
| C++ Dev | Low — Markdown/shell only. |
| Python Dev | Low — Markdown/shell only. |

## Scores

| Dimension | Score (1-5) |
|---|---|
| Complexity | 2 |
| Time to value | 4 |
| Token efficiency | N/A |
| ServiceNow/AI Foundry fit | 4 |
