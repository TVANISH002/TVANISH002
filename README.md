
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-Systems-16a34a?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-Pipelines-0f6e56?style=for-the-badge)
![LLM](https://img.shields.io/badge/LLM-Systems-534ab7?style=for-the-badge)
![Vector Search](https://img.shields.io/badge/Vector%20Search-FAISS%20%7C%20ChromaDB-0f6e56?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-16a34a?style=for-the-badge)
![Infra](https://img.shields.io/badge/Docker%20%7C%20CI--CD%20%7C%20Azure-Infra-534ab7?style=for-the-badge)

# Anish Tirumala Venkata

I build **LLM-powered systems** that retrieve, reason, and generate **grounded outputs** from live data.

---

## Selected Systems

### Agentic Research Intelligence Platform
Multi-agent orchestration for automated research workflows
`Planner → Search → Scrape → Retrieve → Writer → Evaluator`
- **~15–20s end-to-end latency** across complex multi-hop queries
- 5–8 live sources per query with citation-backed outputs
- 50+ query evaluation using **LLM-as-Judge** (relevance, faithfulness, completeness)
- Each agent independently testable — production-style modular control

→ [GitHub](https://github.com/TVANISH002/Agentic-Research-Platform)

---

### ResearchGPT-Enterprise
Grounded Q&A over large document corpora
- **Retrieval relevance lifted from 65% to 82%** through chunking + embedding strategy
- 10,000+ chunks indexed with FAISS-based semantic retrieval
- Hallucination risk reduced via strict retrieval grounding
- FastAPI inference service — built for deployment, not just notebooks

→ [GitHub](https://github.com/TVANISH002/Enterprise-RAG-AI-Assistant)

---

### Job2Mail
AI-powered cold outreach automation
- End-to-end LLM pipeline: job description → portfolio retrieval → personalized email
- ChromaDB semantic search for context selection before generation
- Modular 3-stage architecture (ingestion → retrieval → generation)
- GitHub Actions CI for reliable builds

→ [GitHub](https://github.com/TVANISH002/job2mail-ai-cold-outreach)

---

### Credit Risk Modeling
ML inference system with production REST API
- **P95 latency reduced by 39%** (2.7ms → 1.6ms)
- SMOTE-Tomek for class imbalance, scikit-learn + FastAPI
- Containerized with Docker, CI/CD via GitHub Actions

→ [GitHub](https://github.com/TVANISH002/credit-risk-modeling)

---

## Stack

| Area | Tools |
|---|---|
| LLM Systems | Agentic AI, RAG, LLM Evaluation, Prompting |
| Retrieval | FAISS, ChromaDB, Pinecone, Embeddings |
| Backend | FastAPI, REST APIs, Pydantic |
| Infra | Docker, GitHub Actions, Azure, AWS |
| ML / Data | scikit-learn, Pandas, NumPy |
| Models | GPT-4o, LLaMA 3, Mistral, Gemini |

---

## Currently Building
- More robust agentic systems with stronger evaluation loops
- Production-ready RAG workflows with measurable retrieval quality
- Cloud-deployed AI services on Azure

---

## Links
Portfolio → [tvanish002.github.io](https://tvanish002.github.io)  
LinkedIn → [https://www.linkedin.com/in/anish-tv]
Medium → [ https://medium.com/@anish9]






















