# Claude Knowledge Assistant (RAG + LangChain)

This project is a Retrieval-Augmented Generation (RAG) application built using LangChain to answer questions based on Claude documentation.

Instead of relying only on a language model’s memory, this system retrieves relevant information from Claude docs and generates accurate, context-aware responses.

## 🚀 Features
- Ingests Claude documentation as knowledge base
- Splits documents into chunks for efficient retrieval
- Generates embeddings for semantic search
- Uses vector database to retrieve relevant context
- Provides accurate answers grounded in documentation

## 🧠 Use Case
This project acts as an **AI-powered assistant for Claude documentation**, allowing users to:
- Ask questions about Claude
- Retrieve relevant information instantly
- Get context-aware answers instead of generic responses

## 🛠 Tech Stack
- Python
- LangChain
- Vector Database (FAISS / ChromaDB)
- Embeddings Model
- LLM (Claude / OpenAI)

## 📁 Project Structure
- `Data/` — Claude documentation files
- `Notebook/` — experiments and testing
- `main.py` — main RAG pipeline
- `requirements.txt` — dependencies
- `pyproject.toml` — project configuration
- `uv.lock` — locked dependencies

## ⚙️ How It Works
1. Load Claude documentation
2. Split documents into chunks
3. Generate embeddings for each chunk
4. Store embeddings in a vector database
5. Accept user query
6. Retrieve relevant document chunks
7. Pass context + query to LLM
8. Generate final answer

## 💻 Installation

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
