# Iyman Ahmed

AI engineer building LLM systems that can be measured, not just demoed.
Founder of [CarbonProxy](https://carbonproxy.net). MSc Artificial Intelligence Strategy, Brunel University London. Based in California.

Most LLM demos look fine until someone changes a prompt, swaps a model or shrinks the context.
My work is about catching that: evaluation gates in CI, traced agent runs, and results reported
with their baselines and their limits.

### Selected work

| Project | What it does | Evidence |
|---|---|---|
| **[RAGOps](https://github.com/Iyman-Ahmed/ragops)** | CI gate that fails a pull request when RAG retrieval quality regresses | Caught 4/4 seeded regressions, 0/2 false alarms on controls |
| **[AgentGates](https://github.com/Iyman-Ahmed/agentgates)** | Flight recorder for AI agents: record traces, detect silent failures, gate deploys | Pins each silent failure to the step that caused it |
| **[AI Legal Contract Analyzer](https://github.com/Iyman-Ahmed/ai-legal-contract-analyzer)** | Hybrid-retrieval RAG for clause-level contract risk, checked by an LLM judge | 90.0% / 96.8% clause-type precision / recall on 50 synthetic contracts |
| **[ScoutAI](https://github.com/Iyman-Ahmed/ScoutAI--Smart-company-analyst-agent)** | Three parallel LangGraph agents turn a company name into a financial intelligence report | Under 90 seconds, $0 API cost |
| **[CarbonProxy](https://carbonproxy.net)** | Turns utility bills into audit-ready Scope 1/2/3 carbon reports. The LLM reads; code computes | Every figure links back to its source-document page |

### Stack

Python · TypeScript · LangGraph · LangChain · Claude · FastAPI · ChromaDB · MLflow · Prometheus · Docker · Terraform · GitHub Actions · Next.js

📫 contact@iyman-ahmed.tech · [iyman-ahmed.tech](https://iyman-ahmed.tech) · [LinkedIn](https://www.linkedin.com/in/iyman-ahmed-370061176/)
