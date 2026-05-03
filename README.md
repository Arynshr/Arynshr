<div align="center">

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│   ▄▀█ █▀█ █▄█ ▄▀█ █▄░█   █▀ █░█ ▄▀█ █▀█ █▀▄▀█ ▄▀█   │
│   █▀█ █▀▄ ░█░ █▀█ █░▀█   ▄█ █▀█ █▀█ █▀▄ █░▀░█ █▀█   │
│                                                         │
│         CS Undergrad · Applied AI & Systems             │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

[![GitHub](https://img.shields.io/badge/GitHub-Arynshr-181717?style=flat-square&logo=github)](https://github.com/Arynshr)
[![Email](https://img.shields.io/badge/Email-aryan.shr.04@gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:aryan.shr.04@gmail.com)

</div>

---

I build backend systems and applied ML pipelines — retrieval systems, LLM inference workflows, and evaluation-driven architectures. Currently focused on hybrid search and RAG systems. I read papers, implement them, and validate results.

---

## `$ whoami`

```python
aryan = {
    "role"      : "Applied AI/ML · Backend · Systems",
    "education" : "B.Tech CSE · JIIT Noida",
    "building"  : ["LLM inference pipelines", "hybrid retrieval systems", "RL environments"],
    "open_to"   : ["SDE", "Backend Engineering", "AI/ML Engineering", "Data Engineering"],
}
```

---

## `$ cat stack.json`

| Domain | Technologies |
|---|---|
| **Languages** | Python · C/C++ · SQL |
| **Backend** | FastAPI · Async Python · REST · WebSockets · Pydantic · SQLAlchemy · PostgreSQL |
| **AI / ML** | NLP · Transformers (BERT, FlanT5) · Scikit-learn · Reinforcement Learning · spaCy |
| **Retrieval** | BM25 · FAISS · Qdrant · Dense + Sparse Search · RRF · CrossEncoder Reranking |
| **LLM Tooling** | OpenAI SDK · Groq API · LangChain · RAG Pipelines · Prompt Engineering |
| **Infra & Dev** | Docker · Git · pytest · Linux CLI · SQLite · MySQL |

---

## `$ ls -la ./projects/`

### 🔹 [InventOps](https://github.com/Arynshr/InventOps) — RL Supply Chain Simulation Engine
```
Stack: Python · FastAPI · Groq (Llama-3.1) · OpenAI SDK · Docker · pytest · Pydantic v2
```
> OpenEnv-style RL environment for multi-echelon supply chain optimization

- Modeled stochastic demand across **25 SKUs** with multi-warehouse setups and configurable difficulty levels
- Reduced LLM observation token size by **87%** via optimized state serialization in a Groq/Llama-3.1 pipeline
- Built as a Dockerized FastAPI service with a **17-test pytest suite** for validation

---

### 🔹 [Scipher](https://github.com/Arynshr/Scipher) — Document ETL & NLP Pipeline
```
Stack: Python · FastAPI · Docling · BERT · FlanT5 · spaCy · SQLAlchemy · SQLite · Docker
```
> Multi-stage pipeline for converting academic PDFs into structured data

- End-to-end flow: parsing → section classification (BERT, **92% accuracy**) → NER (spaCy) → summarization (FlanT5) → glossary generation
- Async FastAPI service with WebSocket support, Pydantic-validated I/O, and integrated logging

---

### 🔹 [HybridIR](https://github.com/Arynshr/Neural_search) — Hybrid Retrieval System *(ongoing)*
```
Stack: Python · FastAPI · BM25 · Qdrant · sentence-transformers · CrossEncoder · Groq API · Tavily
```
> Hybrid search system combining sparse and dense retrieval with reranking

- BM25 + Qdrant dense retrieval fused via **Reciprocal Rank Fusion (RRF)** with CrossEncoder reranking
- Evaluated on labeled queries using **Precision@K, MRR, nDCG@5**; targeting measurable improvement over BM25 baseline
- Web-augmented retrieval via Tavily; side-by-side retrieval comparison UI via Textual

---

### 🔹 [TokenFlow](https://github.com/Arynshr/TokenFlow) + [BPE Implementation](https://github.com/Arynshr/Paper-Implementation) — Subword Tokenization
```
Stack: Python · NLTK · Regex · FastAPI · Pydantic · JSON · Pickle
```
> Implementation of Sennrich et al. (2016) BPE for Neural Machine Translation

- Built merge-rule learning, subword segmentation, and vocabulary construction from scratch
- Configurable tokenizer with Unicode (NFKC) normalization, regex-based preprocessing, and pair statistics caching
- Compared OOV handling against word-level and character-level baselines

---

## `$ cat /proc/current`

```
→ Extending HybridIR: query routing + multi-stage reranking + web-augmented retrieval
→ Evaluating LLM pipelines across latency and output quality tradeoffs
→ Studying IR metrics, vector indexing, and inference optimization
```

---

## `$ echo $CONTACT`

```bash
# Open to: SDE · Backend Engineering · AI/ML Engineering · Data Engineering

echo "aryan.shr.04@gmail.com"
open "https://linkedin.com/in/arynshrma"
```

---
