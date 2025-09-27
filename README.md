# Agentic AI Workflows for Enterprise (NVIDIA Workshop Notes)

This repository contains my personal workshop notebooks and notes from the NVIDIA "Learn to Build Agentic AI Workflows for Enterprise Applications" series.  
It is published for reference and learning purposes only. Please do NOT open pull requests or feature requests—this is not an open contribution project.

---

## Contents

| Order | Notebook | Theme / Focus |
|-------|----------|---------------|
| 0 | [00_Introduction.ipynb](./00_Introduction.ipynb) | Workshop overview, framing of agentic systems |
| 1 | [01_Surge_of_Agents.ipynb](./01_Surge_of_Agents.ipynb) | The rise of AI agents & enterprise applicability |
| 2 | [02_AgentIQ_First_Contact.ipynb](./02_AgentIQ_First_Contact.ipynb) | First interaction with AgentIQ concepts/tools |
| 3 | [03_Build_A_Math_Pro_Agent.ipynb](./03_Build_A_Math_Pro_Agent.ipynb) | Constructing a specialized reasoning/math agent |
| 4 | [04_Evals_And_o11y.ipynb](./04_Evals_And_o11y.ipynb) | Evaluation strategies & observability (metrics, tracing) |
| 5 | [05_RAG_It_Is_Ragtime.ipynb](./05_RAG_It_Is_Ragtime.ipynb) | Retrieval-Augmented Generation workflow design |
| 6 | [06_Surge_of_Agents_with_AgentIQ.ipynb](./06_Surge_of_Agents_with_AgentIQ.ipynb) | Scaling multi-agent patterns with AgentIQ |
| — | [workshop_notes.txt](./workshop_notes.txt) | Raw text notes captured during the sessions |

---

## Notebook Overview

### 00_Introduction.ipynb
Sets the stage: enterprise constraints, agent definitions, and how classical workflow orchestration differs from agent-driven adaptation.

### 01_Surge_of_Agents.ipynb
Explores why *now* for agent ecosystems: tooling maturity, model capabilities, cost dynamics, governance expectations.

### 02_AgentIQ_First_Contact.ipynb
Early hands-on with an AgentIQ-style pattern (likely: capability routing, tool brokering, goal decomposition).

### 03_Build_A_Math_Pro_Agent.ipynb
Focus on structured reasoning:  
- Potential use of function/tool calling  
- Guardrails for deterministic steps  
- Evaluating correctness vs. fluency

### 04_Evals_And_o11y.ipynb
Evaluation (Evals) + Observability (o11y):  
- Qualitative vs. quantitative eval loops  
- Traces / spans / step timing  
- Drift & regression detection concepts

### 05_RAG_It_Is_Ragtime.ipynb
Core RAG pipeline design:  
- Chunking trade‑offs (semantic vs. structural)  
- Embedding selection considerations  
- Caching / freshness models for enterprise content

### 06_Surge_of_Agents_with_AgentIQ.ipynb
Scaling multi-agent orchestration: coordination logic, failure recovery, escalation paths, and potential cost/latency optimization heuristics.

### workshop_notes.txt
Unpolished linear notes (ideas, TODOs, observations) preserved verbatim.

---

## How to Use This Repository

1. Open notebooks in JupyterLab, VS Code, or a hosted environment (e.g. local conda + `jupyter lab`).
2. Run cells top-to-bottom; some notebooks may assume:
   - Access to GPU (optional but beneficial)
   - Environment variables for API keys (LLM providers, vector DB, etc.)
3. Treat outputs as exploratory—NOT production-hardened code.

---

## Suggested Environment (Indicative Only)

Because the notebooks are self-contained, dependencies are not codified here. Typical stack you may need:

- Python 3.10+
- JupyterLab or Notebook
- Common AI / data packages (e.g. `langchain`, `numpy`, `pandas`, `tqdm`, `openai` or other model SDKs, vector DB client libraries)

(If you adapt this for your own use, create a `requirements.txt` or `environment.yml`—intentionally omitted here.)

---

## Scope & Intent

This is an educational artifact:
- Not a turnkey product
- No guarantee of completeness or correctness
- Not optimized for performance, pricing, or security
- Some steps may be intentionally manual to illustrate reasoning

---

## No Contributions / Issues

Please do not:
- Open pull requests
- File issues or feature requests
- Request roadmap changes

If you fork it, feel free to tailor it to your own workflow or internal enablement.

---

## Potential Extensions (If You Fork)

- Add environment + dependency management
- Inline tracing (e.g. OpenTelemetry) wrappers
- Integrate automated eval harness
- Modularize agent definitions into Python packages
- Add dataset versioning (e.g. with DVC)

---

## License / Usage

No explicit license is declared. By default, that means all rights are reserved.  
If you need reuse permissions, fork privately or contact the owner.

---

## Attribution

Workshop theme: NVIDIA Agentic AI for Enterprise Applications.  
This repository content: personal adaptation & experimentation.

---

## Quick Start (Example Flow)

1. Start with [00_Introduction.ipynb](./00_Introduction.ipynb)  
2. Skim conceptual framing in [01_Surge_of_Agents.ipynb](./01_Surge_of_Agents.ipynb)  
3. Dive into first applied build in [02_AgentIQ_First_Contact.ipynb](./02_AgentIQ_First_Contact.ipynb)  
4. Explore reasoning specialization in [03_Build_A_Math_Pro_Agent.ipynb](./03_Build_A_Math_Pro_Agent.ipynb)  
5. Add evaluation rigor via [04_Evals_And_o11y.ipynb](./04_Evals_And_o11y.ipynb)  
6. Layer retrieval patterns with [05_RAG_It_Is_Ragtime.ipynb](./05_RAG_It_Is_Ragtime.ipynb)  
7. Scale orchestration via [06_Surge_of_Agents_with_AgentIQ.ipynb](./06_Surge_of_Agents_with_AgentIQ.ipynb)  
8. Consult [workshop_notes.txt](./workshop_notes.txt) for raw contextual scraps.

---

## Disclaimer

All notebooks are snapshot experiments. Execution order, model APIs, or third‑party services may have changed since creation.

---

Enjoy exploring the agentic workflow patterns.