# 🤖 Production-Stable RAG Assistant

A full-stack Retrieval-Augmented Generation (RAG) application that allows users to upload PDF documents and have real-time, context-aware conversations. This project leverages **LangChain**, **Groq (Llama 3.3 70B)**, and **FastAPI**.

## 🚀 Features
*   **PDF Ingestion:** Automatic text extraction and chunking using `PyPDFLoader` and `RecursiveCharacterTextSplitter`.
*   **Vector Search:** Local high-performance vector storage using **FAISS**.
*   **Open Source Embeddings:** Uses HuggingFace's `all-MiniLM-L6-v2` for efficient local embedding generation.
*   **Lightning-Fast LLM:** Powered by Groq's `llama-3.3-70b-versatile` for near-instant responses.
*   **Modern Web UI:** A responsive, dark-themed interface for uploading files and chatting.
*   **Public Tunneling:** Integrated with **ngrok** to make your local server accessible via a public URL immediately.

---

## 🛠️ Tech Stack
*   **Language:** Python
*   **LLM API:** Groq (Llama-3.3-70b)
*   **Frameworks:** LangChain, FastAPI
*   **Vector DB:** FAISS
*   **Embedding Model:** sentence-transformers (`all-MiniLM-L6-v2`)
*   **Deployment:** Uvicorn + ngrok

---

## ⚙️ Quick Start

1. **Install Dependencies:**
   ```bash
   pip install langchain langchain-community langchain-groq faiss-cpu pypdf fastapi uvicorn pyngrok sentence-transformers
