# smtg-ai/claude-squad

**URL:** https://github.com/smtg-ai/claude-squad
**List:** claude-code
**Recommendation:** TBD

## Summary

Terminal app orchestrating multiple AI agents (Claude Code, Aider, Codex, Gemini) in isolated workspaces. Go (87.9%), Shell, TypeScript, CSS. tmux session isolation, git worktrees per branch. Background task completion with auto-accept modes, unified TUI, safe code review before applying changes.

## Would / Would Not

**Would:** Go binary, low overhead; unified TUI for multi-agent coordination fills a real gap when running parallel Claude Code sessions. Auto-accept mode for background tasks is a practical time-saver.

**Would not:** tmux dependency; overlaps with agtx and ccpm — need to pick one multi-agent orchestration approach.

## Persona Notes

| Persona | Notes |
|---|---|
| AI Researcher | High — multi-agent session isolation and coordination architecture, TUI design for agent supervision. |
| C++ Dev | High — Go (similar systems-level concerns), tmux process management, architecture directly relevant. |
| Python Dev | Low — Go binary, limited Python touchpoints. |

## Scores

| Dimension | Score (1-5) |
|---|---|
| Complexity | 3 |
| Time to value | 4 |
| Token efficiency | N/A |
| ServiceNow/AI Foundry fit | 3 |
