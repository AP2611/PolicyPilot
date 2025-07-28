# PolicyPilot

# 🧠 Document QA System using LangChain & LLMs

This project allows users to query large unstructured documents (PDFs such as contracts, policies, and emails) using natural language. It uses **LangChain**, **LLMs**, and **RAG (Retrieval-Augmented Generation)** to extract meaningful answers from your documents.

---

## 🚀 Features

- 📄 Load and parse PDF documents from a directory
- 🧩 Chunk and embed documents for semantic search
- 🔍 Ask natural language questions over your documents
- 🧠 Powered by open-source or commercial LLMs (Mistral, GPT-4, Claude, etc.)
- ✅ Easily extendable for emails, HTML, DOCX, or more file types

---

## 📦 Requirements

Make sure you have **Python 3.9+**
Make sure you have **ollama and mistral**
Also make a folder named data to store all your pdfs 

Install dependencies:

```bash
pip install -U langchain langchain-community openai sentence-transformers faiss-cpu


