# MedAssist AI — RAG-Based Medical Customer Support Assistant

## Overview
MedAssist AI is a RAG-based customer support assistant built using LangGraph, ChromaDB, and HuggingFace.

The system processes medical and insurance PDFs, retrieves contextual information, and generates intelligent responses using Retrieval-Augmented Generation (RAG).

It also supports Human-in-the-Loop (HITL) escalation for emergency queries.

---

## Features
- PDF-based knowledge retrieval
- ChromaDB vector storage
- LangGraph workflow orchestration
- Emergency escalation system
- Human-in-the-Loop support
- Intent-based routing

---

## Tech Stack
- Python
- LangChain
- LangGraph
- ChromaDB
- HuggingFace Transformers
- Sentence Transformers

---

## Workflow
PDF → Chunking → Embeddings → ChromaDB → Retrieval → Response Generation → HITL

---

## Project Structure
``` id="5e5uxj"
medassist-ai-rag-system/
│
├── MedAssist_AI_RAG_Project.ipynb
├── HLD_MedAssist_AI.pdf
├── LLD_MedAssist_AI.pdf
├── Technical_Documentation_MedAssist_AI.pdf
├── README.md
```

---

## Future Improvements
- Multi-document support
- Better retrieval ranking
- Web interface
- Real-time hospital integration
- Memory-enabled conversations

---

## Author
Isha Tilotiya
