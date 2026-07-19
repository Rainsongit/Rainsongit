<!--
  GitHub PROFILE README for Rainsongit.
  → In the repo named exactly  Rainsongit  (github.com/Rainsongit/Rainsongit),
    replace README.md with this, and upload  lattice_benchmark.svg  next to it.
  Links assume lattice-gateway, repolens, sec-filings-rag, Hallucinations_VLMs
  are on the Rainsongit account. Add the sec-filings-rag live demo URL once deployed.
-->

<div align="center">

# Pranay Reddy Baireddy

### I build LLM systems that stay fast under load — and refuse to hallucinate when they don't know.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)

**M.S. Applied AI** · Stevens Institute of Technology · Jersey City, NJ

</div>

---

## 🚀 Featured projects

| Project | Summary | Results |
|---|---|---|
| **[lattice-gateway](https://github.com/Rainsongit/lattice-gateway)** | A fault-tolerant gateway in front of a fleet of model servers — routing, circuit breakers, batching, semantic cache | Handles **2.5× more traffic before saturation** and cuts latency **63%** (p50 223→83 ms); reroutes automatically when a backend fails. 32 tests. |
| **[repolens](https://github.com/Rainsongit/repolens)** | Ask questions about any codebase — grounded answers with source citations | **Never invents an answer** — cites the exact file, and CI fails the build if retrieval quality drops. Zero runtime dependencies. |
| **[sec-filings-rag](https://github.com/Rainsongit/sec-filings-rag)** | Ask questions over 10-K filings; **refuses to answer outside the retrieved evidence** | Answers only what the filings support and refuses everything else — held to **100% on both retrieval and refusal** by an eval gate in CI. FastAPI + React, Docker. |

<div align="center">
  <img src="lattice_benchmark.svg" alt="lattice-gateway: 2.5x throughput, 63% lower p50 latency" width="720" />
</div>

The thread across all three: **measure it, and refuse to guess.**

> ### A system without an eval harness is a demo, not a system.

---

## 🔍 Ask me about

- Why **power-of-two-choices** routing beats least-connections when your load stats are stale
- How a semantic cache can **silently block the event loop** — and the O(1) fix that cut p50 from **87 → 4 ms**
- Designing an **eval gate that fails CI** the moment retrieval quality regresses
- Why naively composing two hallucination fixes made the model **worse**, not better

---

## 🔬 Research

Built an **adaptive hallucination-mitigation framework for vision-language models** that improved F1 by **3.6 points across 9,000 benchmark queries** by routing between decoding strategies based on the model's own uncertainty.
→ **[Report & code](https://github.com/Rainsongit/Hallucinations_VLMs)** *(paper in progress)*

---

## 🧰 Stack

**Languages** — Python · TypeScript · C++ · SQL &nbsp;•&nbsp; **Infra** — Docker · FastAPI · CI/CD · Prometheus · PostgreSQL · AWS/GCP &nbsp;•&nbsp; **AI** — PyTorch · Transformers · RAG · vector search

Currently focused on **reliable agent systems, inference infrastructure, and evaluation.**

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/pranaybaireddy)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:pranaybaireddy08@gmail.com)

</div>
