# Chorus-AIDLC/Chorus

**URL:** https://github.com/Chorus-AIDLC/Chorus
**List:** claude-code
**Recommendation:** TBD

## Summary

AI-DLC (AI-Driven Development Lifecycle) platform — full project lifecycle via multi-agent collaboration (PM, Developer, Admin + humans). Next.js 15, React 19, TypeScript, PostgreSQL 16, Prisma, Redis, MCP HTTP Streamable Transport. DAG task dependency visualization, multi-tenant, AWS CDK deployment. "Reversed conversation": AI proposes, humans verify.

## Would / Would Not

**Would:** Reversed conversation paradigm and DAG dependency management are architecturally interesting — session observability and audit trails are production-grade features worth studying for AI Foundry research.

**Would not:** Full Next.js + PostgreSQL + Redis + AWS setup is significant overhead for individual evaluation. Designed for team deployment.

## Persona Notes

| Persona | Notes |
|---|---|
| AI Researcher | High — AI-DLC methodology, reversed conversation paradigm, multi-agent consensus are core research topics. |
| C++ Dev | Low — TypeScript/JavaScript stack. |
| Python Dev | Medium — MCP HTTP Streamable Transport patterns, multi-agent session management. |

## Scores

| Dimension | Score (1-5) |
|---|---|
| Complexity | 5 |
| Time to value | 2 |
| Token efficiency | N/A |
| ServiceNow/AI Foundry fit | 3 |
