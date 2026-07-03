# Venkateswara Rao Jannegorla

**Agentic AI Engineer** — I build and ship LLM-powered systems to production.

Currently @ USF leading research on **PAAIM** — a multi-agent orchestration system for manufacturing that coordinates 5 specialist agents (safety, quality, maintenance, production, energy) under a machine-readable policy engine with bounded-autonomy constraints, human approval gates, and a Decision Twin for counterfactual impact simulation. Targeting journal publication 2026.

📍 Tampa, FL &nbsp;|&nbsp; F-1 STEM OPT &nbsp;|&nbsp; [Portfolio](https://venky18-portfolio.vercel.app) &nbsp;|&nbsp; [LinkedIn](https://linkedin.com/in/venkateswara-rao-jannegorla-876890241)

---

## What I've shipped

### 🤖 [LeadOps — Autonomous Lead Qualification Agent](https://github.com/VenkateswaraRao18/leadops-dashboard)
`LangGraph` `Gemini` `FastAPI` `Next.js` `Engram` `Langfuse` `PostgreSQL` `Render`

Inbound leads hit a FastAPI webhook → pass through a LangGraph state machine (memory load → intake → scoring → routing → memory save) → get scored 0–100 by Gemini on intent and company context → auto-routed to hot/warm/cold workflows. Returning leads are re-scored with full prior interaction history injected via Engram. Every node traced in Langfuse with latency, token counts, and outputs. Live on Render with a Next.js dashboard.

---

### 🏢 [TechCorp Internal Knowledge Assistant](https://github.com/VenkateswaraRao18/Enterprise-Rag-Assistant) — [Live Demo](https://dthh8ilmdbf8n.cloudfront.net)
`FastAPI` `Qdrant` `AWS Fargate` `CloudFront` `CI/CD` `Gemini`

Production RAG system over Slack, Jira, runbooks, and incident data. ACL/RBAC-aware hybrid retrieval (BM25 + dense + RRF), citation-enforced generation, and security guardrails — **94% retrieval accuracy**. Deployed on AWS Fargate + CloudFront via GitHub Actions CI/CD with latency and guardrail-violation monitoring.

---

### 🔧 [IT Ops RAG Copilot](https://github.com/VenkateswaraRao18/agentic_rag) — [Live Demo](https://agentic-rag-seven.vercel.app)
`LangGraph` `LangChain` `FastAPI` `Next.js` `FAISS` `AWS Bedrock` `Vercel`

Full-stack agentic ops copilot: LangGraph agent with dynamic routing, retrieval over FAISS-embedded docs, tool calls, and cited responses. FastAPI backend + Next.js chat UI with real-time streaming. Bedrock-optional fallback and prompt-level guardrails.

---

### 📦 [DocuWeave — Open-Source PyPI Library](https://github.com/VenkateswaraRao18/docuweave) — [PyPI](https://pypi.org/project/docuweave/)
`Python` `RAG` `PDF Parsing` `FAISS` `Pinecone` `Qdrant`

Layout-aware PDF ingestion pipeline for RAG workloads. **2.9× faster than LangChain** (22s vs 65s). Configurable chunking (fixed-size, sliding-window, semantic boundary) with unified FAISS, Pinecone, and Qdrant integrations.

![PyPI Downloads](https://img.shields.io/pypi/dm/docuweave?label=monthly%20downloads&color=blue)
![PyPI Version](https://img.shields.io/pypi/v/docuweave)

---

### 🧠 [Engram — Long-Term Memory Engine](https://github.com/VenkateswaraRao18/Engram)
`Python` `Neo4j` `Qdrant` `FAISS` `sqlite-vec` `Temporal Knowledge Graph`

Memory engine combining vector search (Qdrant, FAISS, sqlite-vec) with a Neo4j temporal knowledge graph fused via RRF. Implements temporal fact resolution, contradiction detection, importance-weighted memory decay, and episodic summarization for correct multi-session LLM state. **Currently powering LeadOps in production.**

---

### 🏭 [Manufacturing Process Intelligence](https://github.com/VenkateswaraRao18/manufacturing-process-intelligence) — [Live Demo](https://manufacturing-process-intelligence-v.streamlit.app/)
`XGBoost` `scikit-learn` `Streamlit` `FastAPI` `Docker` `UMAP`

End-to-end ML system on a real automotive assembly dataset (143K rows, 2,869 vehicles, 512 features): multi-label classifier at **76.9% micro-precision** across 325 labels, variant discovery via PCA + KMeans + UMAP, and dual-signal anomaly detector (Isolation Forest + model-deviation scoring). Deployed as Streamlit dashboard + FastAPI REST API in Docker.

---

## Stack

```
Agentic:     LangGraph · LangChain · LlamaIndex · MCP · CrewAI
LLM APIs:    OpenAI · Anthropic Claude · Gemini · AWS Bedrock · LLaMA
RAG:         Hybrid Search (BM25 + Dense) · RRF · FAISS · Qdrant · Pinecone · Weaviate
Eval:        Langfuse · LLM Eval Frameworks · Guardrails · Faithfulness Scoring
Backend:     FastAPI · Flask · Python · PostgreSQL · Docker
Frontend:    Next.js · React · TypeScript
Cloud:       AWS (ECS · Fargate · CloudFront) · Render · Vercel · GitHub Actions
ML:          PyTorch · HuggingFace · scikit-learn · XGBoost · LoRA · PEFT
```

---

## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=VenkateswaraRao18&show_icons=true&theme=dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=VenkateswaraRao18&layout=compact&theme=dark&hide_border=true)

---

## Publications

- **Phishing Detection: A Predictive Model for Cyber Security** — IEEE, 2023
- **Secure Document Storage Using Web3** — Scopus, 2024
