<div align="center">

# Venkateswara Rao Jannegorla

### Agentic AI Engineer · Tampa, FL · F-1 STEM OPT

I don't build demos. I build systems that run in production.

[![Portfolio](https://img.shields.io/badge/Portfolio-venky18--portfolio.vercel.app-black?style=flat-square&logo=vercel)](https://venky18-portfolio.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/venkateswara-rao-jannegorla-876890241)
[![PyPI](https://img.shields.io/pypi/dm/docuweave?label=DocuWeave%20downloads%2Fmo&style=flat-square&color=blue)](https://pypi.org/project/docuweave/)

</div>

---

## What I'm building right now

**PAAIM** at USF — a multi-agent system for manufacturing where 5 specialist agents (safety, quality, maintenance, production, energy) coordinate under a machine-readable policy engine. Bounded-autonomy constraints, conflict resolution, human approval gates, a Decision Twin for counterfactual impact simulation (downtime, OEE, scrap, order risk), and a Red-Team Agent that challenges the system's own decisions before they execute. Experimental baselines measure prioritization accuracy, policy violation rate, and decision latency. Targeting journal publication 2026.

---

## Shipped

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [LeadOps](https://github.com/VenkateswaraRao18/leadops-dashboard)
**Autonomous lead qualification agent — live on Render**

Inbound leads → FastAPI webhook → LangGraph state machine → Gemini scores 0–100 → auto-routed to hot/warm/cold workflows. Returning leads re-scored with full history from Engram. Every node traced in Langfuse. Next.js dashboard shows the live pipeline.

`LangGraph` `Gemini` `Langfuse` `Engram` `FastAPI` `Next.js` `Render`

</td>
<td width="50%" valign="top">

### 🏢 [TechCorp Knowledge Assistant](https://github.com/VenkateswaraRao18/Enterprise-Rag-Assistant) · [Live](https://dthh8ilmdbf8n.cloudfront.net)
**Production RAG — 94% retrieval accuracy**

Over Slack, Jira, runbooks, and incident data. ACL/RBAC-aware hybrid retrieval (BM25 + dense + RRF), citation-enforced generation, security guardrails. AWS Fargate + CloudFront + GitHub Actions CI/CD + operational monitoring.

`FastAPI` `Qdrant` `AWS Fargate` `CloudFront` `CI/CD`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔧 [IT Ops RAG Copilot](https://github.com/VenkateswaraRao18/agentic_rag) · [Live](https://agentic-rag-seven.vercel.app)
**Full-stack agentic system — deployed on Vercel**

LangGraph agent with dynamic routing, FAISS retrieval, tool calls, and cited responses. Next.js chat UI with real-time streaming. Bedrock-optional fallback and guardrails.

`LangGraph` `LangChain` `FAISS` `FastAPI` `Next.js` `Bedrock`

</td>
<td width="50%" valign="top">

### 🏭 [Manufacturing Process Intelligence](https://github.com/VenkateswaraRao18/manufacturing-process-intelligence) · [Live](https://manufacturing-process-intelligence-v.streamlit.app/)
**End-to-end ML on 143K-row real automotive dataset**

XGBoost multi-label classifier (76.9% micro-precision, 325 labels), variant discovery via PCA + KMeans + UMAP, dual-signal anomaly detector. FastAPI + Streamlit + Docker.

`XGBoost` `scikit-learn` `Streamlit` `FastAPI` `Docker` `UMAP`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📦 [DocuWeave](https://github.com/VenkateswaraRao18/docuweave) · [PyPI](https://pypi.org/project/docuweave/)
**Open-source PDF ingestion library · 500+ downloads/month**

2.9× faster than LangChain (22s vs 65s). Layout-aware chunking, unified FAISS / Pinecone / Qdrant integrations. Published on PyPI.

![Downloads](https://img.shields.io/pypi/dm/docuweave?style=flat-square&color=blue)
![Version](https://img.shields.io/pypi/v/docuweave?style=flat-square)

`Python` `RAG` `PDF Parsing` `Vector Search`

</td>
<td width="50%" valign="top">

### 🧠 [Engram](https://github.com/VenkateswaraRao18/Engram)
**Long-term memory engine — powering LeadOps in production**

Vector search + Neo4j temporal knowledge graph fused via RRF. Temporal fact resolution, contradiction detection, importance-weighted memory decay, and episodic summarization. Agents remember correctly across sessions.

`Neo4j` `Qdrant` `FAISS` `sqlite-vec` `Temporal KG`

</td>
</tr>
</table>

---

## Stack

| Layer | Tools |
|---|---|
| **Agents & Orchestration** | LangGraph · LangChain · LlamaIndex · MCP · CrewAI |
| **LLM APIs** | OpenAI · Anthropic Claude · Gemini · AWS Bedrock · LLaMA |
| **RAG & Retrieval** | Hybrid Search · BM25 + Dense · RRF · FAISS · Qdrant · Pinecone · Weaviate |
| **Eval & Observability** | Langfuse · Guardrails · Faithfulness Scoring · LLM Eval Frameworks |
| **Backend & APIs** | FastAPI · Flask · PostgreSQL · Docker · Python |
| **Frontend** | Next.js · React · TypeScript |
| **Cloud & DevOps** | AWS (ECS · Fargate · CloudFront) · Render · Vercel · GitHub Actions |
| **ML & Training** | PyTorch · HuggingFace · scikit-learn · XGBoost · LoRA · PEFT |

---

## Numbers

```
500+    DocuWeave monthly PyPI downloads
94%     Retrieval accuracy — TechCorp RAG system
76.9%   Micro-precision — Manufacturing ML classifier (325 labels)
2.9×    Faster PDF ingestion than LangChain
```

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=VenkateswaraRao18&show_icons=true&theme=dark&hide_border=true&count_private=true&hide_title=true)

**Open to AI Engineer roles · Tampa, FL or Remote · No sponsorship needed (STEM OPT)**

</div>
