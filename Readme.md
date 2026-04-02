# 📄 PDF AI Assistant

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/LLM-Groq-orange" />
  <img src="https://img.shields.io/badge/VectorDB-PGVector-purple" />
  <img src="https://img.shields.io/badge/PostgreSQL-Database-blue?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Active-success" />
</p>

---

## 🚀 Features

- ✅ Chat with PDF documents using AI  
- ✅ Retrieval-Augmented Generation (RAG)  
- ✅ Persistent chat memory with PostgreSQL  
- ✅ Semantic search using vector database  
- ✅ CLI-based interactive assistant  
- ✅ Supports multi-session conversations  

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=python" height="40"/>
  <img src="https://skillicons.dev/icons?i=postgresql" height="40"/>
  <img src="https://cdn.simpleicons.org/openai/000000" height="40"/>
</p>

- **Phidata (LLM Agent Framework)** :contentReference[oaicite:0]{index=0}  
- **PGVector (Vector Database)** :contentReference[oaicite:1]{index=1}  
- **PostgreSQL (Storage)**  
- **Groq API (LLM inference)**  
- **Typer (CLI Interface)**  

---

## ⚙️ Installation

```bash
git clone <your-repo-link>
cd <your-repo-name>
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
🔑 Environment Setup

Create a .env file:

GROQ_API_KEY=your_api_key_here
▶️ Usage
python pdf_assistant.py
Starts an interactive CLI assistant
Loads PDF knowledge base
Enables conversational querying
💡 Example Use Cases
Ask questions from PDFs
Recipe/document assistants
Study material Q&A
Knowledge retrieval systems
📌 Key Concepts Covered
Retrieval-Augmented Generation (RAG)
Vector embeddings & semantic search
LLM-based assistants
Stateful conversation memory
CLI-based AI tools