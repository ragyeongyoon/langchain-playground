# langchain-playground

A practical playground for building Retrieval-Augmented Generation (RAG) based QA systems using LangChain, FAISS, HuggingFace, and OpenAI.

This repository contains multiple Jupyter notebook implementations created as part of the **Korea University Summer SW·AI Camp 2025**, focusing on large language model applications and prompt engineering.

---

## Curriculum Overview

| Date | Topic |
|------|-------|
| **07.28** | Introduction to LLMs & RAG (Retrieval-Augmented Generation) |
| **07.29** | Prompt Engineering strategies for large language models |
| **07.30** | Frameworks for QA system development (LangChain, Streamlit, etc.) |
| **07.31** | FAISS vector store integration & prompt tuning |
| **08.01** | Full RAG QA pipeline implementation & final review |

---

## Tech Stack

- Python 3.x
- [LangChain](https://github.com/langchain-ai/langchain)
- OpenAI GPT-3.5 / GPT-4
- FAISS (Facebook AI Similarity Search)
- HuggingFace Transformers
- PyMuPDF (for PDF parsing)
- Tiktoken (token counting)
- Streamlit (optional UI)
- dotenv (`.env` environment config)

---

## 📌 Features

- Document ingestion and cleaning (PDF parsing)
- Chunking with `RecursiveCharacterTextSplitter`
- Vector store setup with FAISS
- RAG pipeline: embedding → retrieval → answer generation
- Interchangeable embeddings: OpenAI vs HuggingFace
