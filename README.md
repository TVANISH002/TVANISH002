![Agentic AI](https://img.shields.io/badge/Agentic%20AI-Systems-16a34a?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-Pipelines-0f6e56?style=for-the-badge)
![LLM](https://img.shields.io/badge/LLM-Systems-534ab7?style=for-the-badge)
![Vector Search](https://img.shields.io/badge/Vector%20Search-FAISS%20%7C%20ChromaDB-0f6e56?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-16a34a?style=for-the-badge)
![Infra](https://img.shields.io/badge/Docker%20%7C%20CI--CD%20%7C%20Azure-Infra-534ab7?style=for-the-badge)
 
# Anish Tirumala Venkata
 
**AI Engineer** — M.S. Computer Science @ University of Florida  
I build LLM-powered systems that go beyond demos — grounded retrieval, multi-agent orchestration, and production deployment on real infrastructure.
 
Currently building a RAG-based grant writing assistant deployed on **Azure** at Street Care.  
🔍 Open to **AI Engineer / ML Engineer** roles — graduating Dec 2025.
 
---
 
## What I Build
 
I don't just fine-tune models. I build the full system around them:
 
- **Retrieval pipelines** that actually work — chunking strategy, embedding choice, hybrid search, metadata filtering
- **Agentic workflows** where agents are independently testable and replaceable
- **Evaluation layers** — LLM-as-Judge, retrieval benchmarking, grounding checks — because shipping without measurement isn't production
- **Deployed APIs** — FastAPI, Docker, GitHub Actions CI/CD, Azure Container Apps
---
 
## Projects
 
### 🔬 Agentic Research Intelligence Platform
*Multi-agent orchestration for automated research workflows*
 
`Planner → Search → Scrape → Retrieve → Writer → Evaluator`
 
- **~15–20s end-to-end latency** across complex multi-hop queries
- **5–8 live sources** per query with fully citation-backed outputs
- **50+ query evaluation** using LLM-as-Judge across relevance, faithfulness, and completeness
- Each agent independently testable and replaceable — built for production-style modular control
→ [View on GitHub](https://github.com/TVANISH002/Agentic-Research-Platform)
 
---
 
### 📄 ResearchGPT — Enterprise RAG AI Assistant
*Grounded Q&A over research-paper corpora*
 
- End-to-end RAG system: PDF ingestion → chunking → MiniLM embeddings → FAISS indexing → FastAPI → Streamlit
- Retrieval relevance improved from **68.5% → 80.0%** through iterative tuning of chunk size, overlap, and top-k, plus corpus expansion across RAG, FAISS, BM25, and LoRA papers
- Modular architecture designed to scale toward **10,000+ document chunks**
- Built evaluation utilities for corpus statistics, retrieval benchmarking, and grounding checks
- Strict retrieval-grounded prompting to reduce hallucination risk
→ [View on GitHub](https://github.com/TVANISH002/ResearchGPT--Enterprise-RAG-AI-Assistant)
 
---
 
### ✉️ Job2Mail — AI Cold Outreach Automation
*End-to-end personalized outreach pipeline*
 
- LLM pipeline: job description → ChromaDB semantic retrieval → personalized cold email
- Modular 3-stage architecture: ingestion → retrieval → generation
- Configurable tone, sender profile, and project context for targeted outreach
- GitHub Actions CI runs on every push for stable, deployment-ready builds
→ [View on GitHub](https://github.com/TVANISH002/job2mail-ai-cold-outreach)
 
---
 
### 📊 Credit Risk Modeling — ML Inference API
*Production-grade financial risk classification*
 
- **P95 latency reduced by 39%** — from 2.7ms to 1.6ms — by eliminating redundant preprocessing
- Real-time predictions via FastAPI REST API with end-to-end scikit-learn pipeline
- SMOTE-Tomek for robust class imbalance handling
- Containerized with Docker, CI/CD via GitHub Actions
→ [View on GitHub](https://github.com/TVANISH002/credit-risk-modeling)
 
---
 
## Stack
 
| Area | Tools |
|---|---|
| **LLM & Agents** | Agentic AI, Multi-Agent Orchestration, RAG, LLM Evaluation, LLM-as-Judge, Chain-of-Thought, ReAct |
| **Retrieval** | FAISS, ChromaDB, Pinecone, Azure AI Search, Hybrid Search, text-embedding-3-small, MiniLM |
| **Backend** | FastAPI, REST APIs, Pydantic, Async Processing |
| **Infra** | Docker, GitHub Actions, Azure Container Apps, AWS |
| **ML / NLP** | scikit-learn, PyTorch, HuggingFace, DistilBERT, Pandas, NumPy |
| **Models** | GPT-4o, LLaMA 3, Mistral, Gemini |
 
---
 
## Currently Building
 
- RAG-based grant writing assistant on **Azure** (Street Care) — recursive chunking, metadata filtering, hybrid search
- Stronger evaluation loops across agentic pipelines
- Production-ready RAG workflows with measurable retrieval quality benchmarks
---
 
## Links
 
🌐 Portfolio → [tvanish002.github.io](https://tvanish002.github.io)  
💼 LinkedIn → [linkedin.com/in/anish-tv](https://www.linkedin.com/in/anish-tv)
