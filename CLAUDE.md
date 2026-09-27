# Repository notes

**GitHub repository:** https://github.com/one-piece-of-ai/claude

## Semiconductor Cycle Report routine

- Reports are written to `reports/semi-cycle-report-YYYY-MM-DD.md` and pushed to the default branch (`claude/main`).
- **Always include the GitHub repository link in outputs** (report footer and/or the run's notification), e.g.:
  - Repo: https://github.com/one-piece-of-ai/claude
  - This run's report: https://github.com/one-piece-of-ai/claude/blob/claude/main/reports/semi-cycle-report-YYYY-MM-DD.md

### Standing thesis to track every report: agentic AI → rising CPU reliance

Incorporate this structural trend into every future report (it supplements, does not replace, the existing GPU/HBM/foundry framework):

- **Thesis:** The shift from single-shot LLM inference to *agentic* AI (multi-step reasoning, tool calls, long-running autonomous agents, orchestration loops) increases reliance on **CPUs** and **general-purpose/host compute**, not just GPU accelerators. Agents run many sequential inference + tool/orchestration steps; the host CPU, system memory, networking, and control-plane compute scale with agent count and step depth. This broadens AI demand beyond the pure-GPU-training story toward data-center **server CPUs, memory, and heterogeneous compute**.
- **What to add:**
  1. In **Section 3 (Key Signals — AI-driven demand)**, add a line assessing whether the period's data supports agentic-AI-driven CPU/host-compute demand (e.g. server-CPU commentary, data-center CPU shipments/ASPs, hyperscaler capex mix shifting toward general-purpose compute alongside accelerators).
  2. In **Section 5 (Company Readouts / supporting context)**, track the CPU-side names when they report or guide: **Intel (Xeon/data-center), AMD (EPYC + Instinct), Arm (data-center core licensing/royalties), NVIDIA Grace / custom CPUs, and cloud custom silicon (AWS Graviton, Google Axion, Microsoft Cobalt)**. Note inference-vs-training mix shifts and any "agentic workload" call-outs on earnings.
  3. In **Section 3 (Memory cycle)**, connect agentic inference to **memory intensity** (large KV-caches, long context, high concurrency) as an additional structural support for the DRAM/HBM shortage thesis.
  4. In the **Cycle Positioning Call / What to Watch**, treat agentic-AI CPU demand as a *broadening* signal that can extend the upcycle beyond the GPU-only narrative — flag it as a positive breadth indicator, and watch for evidence it is materializing (server-CPU unit/ASP re-acceleration) vs. still-just-narrative.
- **Discipline:** Keep it data-driven and leading-indicator-focused, same as the rest of the report. Cite sources; if there is no fresh CPU/agentic datapoint in a given period, say so briefly rather than forcing a narrative.
