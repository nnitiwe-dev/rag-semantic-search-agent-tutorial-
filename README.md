# Introduction to RAG: Embeddings, Semantic Search & Vector Databases

This repository contains the source code and resources for the **Retrieval Augmented Generation (RAG)** tutorial featured on **Techlytics**. 

In this session, we break down how embeddings, semantic search, and vector databases work together to build reliable, data-driven AI systems. You will learn how RAG helps ground Large Language Models (LLMs) in trusted data, reduce hallucinations, and improve response quality for real-world enterprise use cases.

## 🎥 Watch the Full Tutorial
Check out the live session for a step-by-step walkthrough:
[**Watch on YouTube**](https://www.youtube.com/live/sOyU_I68MoA?si=ooUA08N3RvWI-Mml&t=806)

---

## 🚀 Key Concepts Covered
* **Embeddings:** Turning text into numerical vectors to capture semantic meaning.
* **Semantic Search:** Moving beyond keyword matching to understand user intent.
* **Vector Databases:** Efficiently storing and retrieving high-dimensional data.
* **RAG Pipeline:** Connecting your own data (e.g., PDFs, documentation) to an LLM to provide accurate, context-aware answers.

## 🛠️ Tech Stack
This implementation uses:
* **Database:** [MongoDB Atlas](https://www.mongodb.com/products/platform/atlas-vector-search) (Vector Search)
* **Embeddings:** [Voyage AI](https://www.voyageai.com/) (`voyage-finance-2`)
* **LLM:** [OpenAI](https://openai.com/)
* **Orchestration:** [LangChain](https://www.langchain.com/)
* **Parsing:** `PyPDF` & `RecursiveCharacterTextSplitter`

## 📋 Prerequisites
To run the notebook, you will need API keys for:
1. **MongoDB Atlas** (Connection String)
2. **Voyage AI** (For embeddings)
3. **OpenAI** (For text generation)

## ⚙️ Installation
Clone the repo and install the required Python libraries:

```bash
pip install pymongo voyageai openai langchain langchain-text-splitters langchain_community pypdf