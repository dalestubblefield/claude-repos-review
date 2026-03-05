# ruvnet/ruflo

**URL:** https://github.com/ruvnet/ruflo
**List:** claude-code
**Recommendation:** TBD

## Summary

Enterprise AI orchestration platform for coordinated multi-agent swarms via Claude. WebAssembly kernels in Rust, PostgreSQL vector DB (RuVector) with HNSW search, ONNX Runtime for local embeddings. Supports Claude/GPT/Gemini/Ollama with intelligent routing and failover. Claims 30-50% API cost reduction.

## Would / Would Not

**Would:** Enterprise-grade orchestration with consensus mechanisms, goal-drift prevention, and real token savings — relevant if AI Foundry scales to team-wide agent swarms.

**Would not:** Rust/WASM + PostgreSQL + ONNX infrastructure is overkill for single-developer ServiceNow projects.

## Persona Notes

| Persona | Notes |
|---|---|
| AI Researcher | High — consensus mechanisms, goal drift prevention, multi-LLM routing are novel research-grade patterns. |
| C++ Dev | High — Rust/WASM kernel is performance-critical, similar problem domain. Architecture worth studying. |
| Python Dev | Medium — ONNX Runtime integration, multi-LLM provider support touchpoints. |

## Scores

| Dimension | Score (1-5) |
|---|---|
| Complexity | 5 |
| Time to value | 1 |
| Token efficiency | 5 |
| ServiceNow/AI Foundry fit | 3 |
