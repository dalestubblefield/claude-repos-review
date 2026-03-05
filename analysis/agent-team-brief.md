# Agent Team Brief — Claude Code Repos Review

**For:** Senior AI Researcher, Senior C++ Developer, Senior Python Developer
**Source list:** https://github.com/stars/dalestubblefield/lists/claude-code
**Purpose:** Evaluate 20 repos and recommend which belong in `claude-pick` (vetted, recommend) vs `claude-passed` (explored, not the right fit).

---

## Context

Dale Stubblefield is a ServiceNow developer at ServiceNow working on the Innovation Pipeline — a Claude Code-assisted scoped app using the Now SDK (Fluent DSL). He uses Claude Code daily with the superpowers plugin workflow (TDD, branch+PR, subagent-driven development). He also leads GitHub governance for the Now-AI-Foundry org (37 repos, 24 members).

**Active stack:** Claude Code, Now SDK (Fluent DSL), TypeScript/Node.js, ServiceNow (gpinst01/aifoundrydev instances), rtk-ai/rtk (already installed), vercel-labs/agent-browser (already installed).

---

## High-Priority Repos by Persona

### AI Researcher

| Repo | Why High Priority |
|---|---|
| ruvnet/ruflo | Consensus mechanisms, goal-drift prevention, multi-LLM routing |
| Chorus-AIDLC/Chorus | AI-DLC methodology, reversed conversation paradigm |
| cortex-tms/cortex-tms | HOT/WARM/COLD doc tiering — cache eviction applied to knowledge |
| groeimetai/snow-flow | ServiceNow-specific multi-agent orchestration taxonomy |
| automazeio/ccpm | GitHub Issues as multi-agent coordination substrate |
| hesreallyhim/awesome-claude-code | Ecosystem map — start here for orientation |
| modelcontextprotocol/servers | MCP protocol design and tool-use patterns |
| cowwoc/cat | Multi-perspective review mechanism and state resumption |
| smtg-ai/claude-squad | Multi-agent session isolation and TUI supervision design |
| anthropics/claude-plugins-official | Plugin architecture governance patterns |

### C++ Developer

| Repo | Why High Priority |
|---|---|
| ruvnet/ruflo | Rust/WASM kernel — performance-critical systems architecture |
| rtk-ai/rtk | Rust single binary, zero-dependency output parser architecture |
| vercel-labs/agent-browser | Rust native binary, sub-millisecond overhead design |
| fynnfluegge/agtx | Rust kanban orchestrator, tmux process management |
| smtg-ai/claude-squad | Go (87.9%), systems-level process isolation patterns |
| modelcontextprotocol/servers | Rust SDK available for MCP server development |
| AThevon/TokenEater | Swift/macOS systems patterns, protocol-based DI |

### Python Developer

| Repo | Why High Priority |
|---|---|
| wshobson/agents | Dedicated Python agent category |
| anthropics/claude-plugins-official | Python is primary language (55.3%) |
| BehiSecc/VibeSec-Skill | Python stack security (SQLi, SSRF, auth) |
| cowwoc/cat | Python-native, directly runnable |
| modelcontextprotocol/servers | Python SDK is primary MCP implementation path |
| hesreallyhim/awesome-claude-code | Python skills and automation section |
| rtk-ai/rtk | Python output parser, directly reduces test/lint token cost |

---

## Clusters Requiring Agent Decision

### Monitoring Tools (pick one)
Three repos do overlapping usage monitoring — agents should recommend the best single tool:
- `sirmalloc/ccstatusline` — terminal status line, estimated metrics
- `pcvelz/ccstatusline-usage` — fork with real API usage metrics
- `ryoppippi/ccusage` — CLI cost analytics from local JSONL
- `AThevon/TokenEater` — macOS menu bar, native Swift

### Multi-Agent Orchestration (pick one)
Three repos solve parallel agent coordination:
- `smtg-ai/claude-squad` — Go TUI, tmux isolation
- `fynnfluegge/agtx` — Rust kanban, tmux + git worktrees
- `automazeio/ccpm` — GitHub Issues as coordination layer

### ServiceNow-Specific (evaluate for licensing)
- `groeimetai/snow-flow` — Elastic License 2.0, needs legal review before AI Foundry customer use

---

## Already In Use (Not Up for Debate)

| Repo | Status |
|---|---|
| rtk-ai/rtk | Installed, active, configured in CLAUDE.md |
| vercel-labs/agent-browser | Installed at /opt/homebrew/bin/agent-browser |
| ServiceNow/sdk | Core project dependency |

---

## Recommendation Output Format

For each repo, agents should produce:

```
**Repo:** owner/name
**Recommendation:** claude-pick | claude-passed | needs-more-info
**Rationale:** 1-2 sentences
**Persona flags:** [AI Researcher: yes/no] [C++ Dev: yes/no] [Python Dev: yes/no]
```
