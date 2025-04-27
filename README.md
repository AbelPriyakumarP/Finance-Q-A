# 📊 Finance Q&A System with RAG, ChromaDB, and Hugging Face Models

This project implements a **Retrieval-Augmented Generation (RAG)** based Question Answering system for the finance domain using **LangChain**, **Chroma vector database**, and **Hugging Face models**. It enables querying over finance-related documents and returns contextual, AI-generated answers using a locally managed vector store.

---

## 📌 Project Overview

The system combines the power of:
- 📚 **ChromaDB** for vector storage and retrieval
- 🤖 **Hugging Face language models** for response generation
- 🧱 **LangChain framework** to orchestrate the entire pipeline

Users can upload finance-related text documents, convert them into vector embeddings, and run natural language queries to receive informed, context-aware answers.

---
## 🗺️ System Architecture

![image alt](https://github.com/AbelPriyakumarP/Finance-Q-A/blob/main/architecture.png?raw=true)

---

## 🛠️ Features

- 📄 Document ingestion from local `.txt` files or URLs
- 🔍 Embedding generation and vector storage using ChromaDB
- 💬 Question answering via Hugging Face-hosted LLM models
- 📈 Persistent vector store for efficient retrieval
- ⚙️ Configurable to support multiple document sources
- ✅ Runs locally without OpenAI APIs (uses `langchain-groq` and Hugging Face)

---

## 📚 Dependencies

- `langchain`
- `chromadb`
- `langchain-groq`
- `huggingface_hub`
- `sentence_transformers`
- `unstructured`
- `tqdm`
- `ipython`
- `python-dotenv`

**Install via:**
```bash
pip install -r requirements.txt

.
├── Finance_Q&A.ipynb          # Main Jupyter Notebook with full pipeline code
├── education_docs.txt         # Sample educational content document
├── finance_docs.txt           # Sample finance knowledge base document
├── chroma_db/                 # Local persistent vector store (auto-generated)
├── README.md                  # Project documentation file
└── requirements.txt           # Python dependencies list

## 🗺️ System Architecture

![RAG Architecture](![ChatGPT Image Apr 27, 2025, 09_10_29 PM](https://github.com/user-attachments/assets/578e61b5-291d-4c7b-83a8-e3b2e35e91f7)
)

git clone https://github.com/yourname/finance-qna-rag.git
cd finance-qna-rag

pip install -r requirements.txt

jupyter notebook

🤝 Contact
For questions or collaborations, reach out at:
📧 roshabel001@gmail.com
🌐 https://www.linkedin.com/in/abel-priyakumar-p/
