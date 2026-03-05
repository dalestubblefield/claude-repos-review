# BehiSecc/VibeSec-Skill

**URL:** https://github.com/BehiSecc/VibeSec-Skill
**List:** claude-code
**Recommendation:** TBD

## Summary

AI skill embedding 5+ years of bug bounty hunting knowledge into LLM code generation. Covers IDOR, XSS, CSRF, SQLi, SSRF, auth weaknesses, API security. Framework-aware (React, Node.js, Python). Installs into `~/.claude/skills`. Prompt-engineering focused rather than code tooling.

## Would / Would Not

**Would:** Low installation friction — drops into existing skills directory. Valuable for any project touching external APIs or user input (relevant to ServiceNow scripted REST APIs and UI Pages).

**Would not:** Effectiveness depends on how well the skill prompts hold up vs. Claude's existing security knowledge — hard to audit without trying it.

## Persona Notes

| Persona | Notes |
|---|---|
| AI Researcher | Medium — prompt-based security knowledge injection as a skill design pattern. |
| C++ Dev | Low — web-focused vulnerabilities, not systems-level. |
| Python Dev | High — covers Python stack (SQLi, SSRF, auth) directly. |

## Scores

| Dimension | Score (1-5) |
|---|---|
| Complexity | 1 |
| Time to value | 5 |
| Token efficiency | N/A |
| ServiceNow/AI Foundry fit | 3 |
