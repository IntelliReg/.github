# 🧠 IntelliReg

### AI-Powered Regulatory Intelligence System

> Making complex regulations intelligent, accessible, and verifiable.

IntelliReg is an AI-powered regulatory intelligence system designed to help users understand and navigate complex, evolving regulatory documents.

Unlike traditional document chatbots, IntelliReg combines **RAG, Knowledge Graphs, and Hybrid Search** to understand relationships between regulations, track regulatory changes over time, and provide context-aware answers with verifiable source citations.

---

## ✨ Key Features

* 🔍 **Intelligent Search** — Ask natural language questions about regulatory documents.
* ⏳ **Temporal Awareness** — Understand regulations based on specific time periods and versions.
* 🕸️ **Knowledge Graph** — Track relationships and supersession between regulatory documents.
* 🔀 **Hybrid Retrieval** — Combine semantic and keyword-based search.
* 📌 **Source Citations** — Trace answers back to their original regulatory documents.
* 📄 **PDF Highlighting** — View the exact source clause supporting an answer.
* 📊 **Regulatory Timeline** — Visualize how regulations evolve over time.
* 🛡️ **Answer Verification** — Validate generated answers against retrieved sources.

---

## 🏗️ How It Works

```text
Regulatory Documents
        │
        ▼
Document Processing
        │
   ┌────┴─────┐
   ▼          ▼
Vector DB   Knowledge Graph
   │          │
   └────┬─────┘
        ▼
  Query Engine
        │
        ▼
   RAG + LLM
        │
        ▼
Verified Answer
```

---

## 🛠️ Tech Stack

| Category        | Technologies               |
| --------------- | -------------------------- |
| Frontend        | Next.js, React, TypeScript |
| Backend         | Python, FastAPI            |
| AI              | RAG, LLMs, Embeddings      |
| Vector Database | Qdrant                     |
| Knowledge Graph | Neo4j                      |
| Evaluation      | RAGAS                      |
| Infrastructure  | Docker, GitHub Actions     |

---

## 🎯 Project Goal

The goal of IntelliReg is to build a system that not only retrieves information from regulatory documents but also understands their **relationships, versions, and evolution over time**, making regulatory research faster, more transparent, and easier to verify.

---

## 📂 Project Structure

```text
intellireg/
├── frontend/          # Next.js application
├── backend/           # FastAPI backend
├── ingestion/         # Document processing
├── retrieval/         # RAG & search pipeline
├── knowledge-graph/   # Graph construction
├── evaluation/        # System evaluation
├── docs/              # Documentation
└── README.md
```

---

## 🚧 Project Status

**Currently under active development.**

See the [project roadmap](./docs) for implementation progress.

---

## 👥 Team

Developed as a collaborative final-year engineering project.

---

<div align="center">

**IntelliReg — AI-Powered Regulatory Intelligence System**

</div>
