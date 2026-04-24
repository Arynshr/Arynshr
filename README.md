<div align="center">

```
╔══════════════════════════════════════════╗
║  ARYAN SHARMA · Software Engineer        ║
║  Backend  ·  AI/ML  ·  Systems           ║
╚══════════════════════════════════════════╝
```
</div>

---

I enjoy building systems that are reliable and efficient — APIs that scale, pipelines that process data effectively, and ML systems that extend beyond experimentation. Currently exploring retrieval systems and LLM infrastructure, with a strong foundation in backend engineering.

---

## `$ whoami`

```python
aryan = {
    "role"      : "Software Engineer  →  Backend · AI/ML · Systems",
    "location"  : "Delhi NCR, India",
    "education" : "B.Tech CSE · JIIT Noida",
    "building"  : ["production APIs", "retrieval systems", "LLM pipelines"],
    "available" : True,   # SDE · Backend · AI/ML
}
```

---

## `$ cat skills.txt`

| | Stack |
|---|---|
| **Languages** | Python · C/C++ · SQL |
| **Backend** | FastAPI · REST · WebSockets · Async Python · Pydantic · SQLAlchemy |
| **AI / ML** | NLP · Transformers · Scikit-learn · RL · Sentence-Transformers |
| **Retrieval** | BM25 · FAISS · Qdrant · RAG · Dense + Sparse Search |
| **LLM Tooling** | OpenAI SDK · Groq API · LangChain |
| **Infra** | Docker · PostgreSQL · Git · pytest · Linux |

---

## `$ ls -l ./projects/`

**[InventOps](https://github.com/Arynshr/InventOps)** — RL-based supply chain simulation engine

```
OpenEnv-compliant · 25 SKUs · multi-warehouse · stochastic demand · 3 difficulty levels
```
- Designed a full RL environment for multi-echelon supply chain optimization with deterministic reward grading
- Cut LLM token usage by **87%** via observation compression on a Groq/Llama-3.1 inference pipeline
- Shipped as a Dockerised FastAPI service, backed by a 17-test pytest suite with RLVR-based prompt tuning

---

**[Scipher](https://github.com/Arynshr/Scipher)** — document intelligence pipeline for research papers

```
FastAPI · Docling · BERT · FlanT5 · async · WebSocket
```
- Multi-stage pipeline: PDF parsing → section classification → entity extraction → summarization + glossary
- BERT classifier hitting **92% section accuracy**; FlanT5 for abstractive summarization
- Async microservice with WebSocket support, Pydantic validation, and structured logging

---

**[HybridIR](https://github.com/Arynshr/Neural_search)** — hybrid search & retrieval system *(ongoing)*

```
BM25 · sentence-transformers · Milvus · RRF · MS MARCO · Precision@K · MRR · nDCG
```
- Combines sparse (BM25) and dense (sentence-transformers + Milvus Lite) retrieval with Reciprocal Rank Fusion
- Evaluation pipeline on MS MARCO with latency benchmarking and metric tracking
- Building agentic query router and live Textual interface for side-by-side retrieval comparison

---

## `$ cat /dev/current`

```
→ Extending HybridIR: agentic query routing + multi-stage RAG
→ Evaluation-driven LLM pipeline optimization
→ Scalable async backend patterns for ML-in-production
```

---

## `$ echo $CONTACT`

```
Open to SDE · Backend · AI/ML · Systems Engineering internships
aryan.shr.04@gmail.com
```

---

<div align="center">
<sub>reads papers · ships code · breaks things · fixes them</sub>
</div>
