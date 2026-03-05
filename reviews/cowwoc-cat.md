# cowwoc/cat

**URL:** https://github.com/cowwoc/cat
**List:** claude-code
**Recommendation:** TBD

## Summary

Claude plugin for structured, spec-driven AI-assisted project delivery. Hierarchical task management, configurable trust/verification/patience levels, isolated Git worktrees, multi-perspective stakeholder reviews, state tracking for resuming after interruptions. Python-based.

## Would / Would Not

**Would:** Structured workflow enforcement (spec → task → verify → resume) addresses "AI goes off-rails on long projects." Stakeholder review gates and worktree isolation align with TDD + branch+PR workflow.

**Would not:** Python dependency in a Node.js/TypeScript-heavy environment adds toolchain friction.

## Persona Notes

| Persona | Notes |
|---|---|
| AI Researcher | High — multi-perspective review mechanism and state resumption patterns are novel workflow research. |
| C++ Dev | Low — Python tooling. |
| Python Dev | High — Python-native, directly runnable, workflow patterns worth studying. |

## Scores

| Dimension | Score (1-5) |
|---|---|
| Complexity | 3 |
| Time to value | 3 |
| Token efficiency | N/A |
| ServiceNow/AI Foundry fit | 3 |
