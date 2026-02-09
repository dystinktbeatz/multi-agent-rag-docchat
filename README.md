# 🤖 DocChat — Multi-Agent RAG Document Assistant

An advanced **Multi-Agent Retrieval-Augmented Generation (RAG)** system that allows users to upload documents and interactively query them with AI.
This project demonstrates how modern AI applications combine **vector search, agentic workflows, document intelligence, and LLM reasoning** to build reliable, production-style document assistants.

---

## 🌟 Why This Project Matters

Large Language Models alone often hallucinate.
DocChat solves this by integrating:

* 📚 Retrieval-Augmented Generation (RAG)
* 🤖 Multi-Agent AI orchestration (LangGraph)
* 🔎 Hybrid semantic + keyword retrieval
* ✔️ AI answer verification pipeline

This results in **more accurate, explainable, and trustworthy AI responses**.

---

## 🚀 Core Features

### 📄 Intelligent Document QA

* Upload PDFs, DOCX, TXT, Markdown files
* Ask natural language questions
* Receive context-grounded answers

### 🤖 Multi-Agent AI Workflow

Agents collaborate to ensure quality:

* **Relevance Agent** → Checks if documents can answer the query
* **Research Agent** → Generates answer from retrieved content
* **Verification Agent** → Validates factual accuracy

This significantly reduces hallucinations.

### 🔍 Hybrid Retrieval Engine

Combines:

* BM25 keyword search (precision)
* Vector embeddings semantic search (context understanding)

Ensures high recall + high relevance.

### 🧠 RAG Pipeline

* Docling document parsing (structured extraction)
* Markdown header chunking
* ChromaDB vector database storage
* WatsonX AI models for reasoning

### 🌐 Interactive UI

* Built using Gradio
* Upload, query, and view responses easily

---

## 🏗️ Architecture Overview

```
User Upload Document
        ↓
Document Parsing (Docling)
        ↓
Chunking + Embeddings
        ↓
Vector DB (ChromaDB)
        ↓
Hybrid Retrieval (BM25 + Semantic)
        ↓
Multi-Agent Workflow (LangGraph)
   → Relevance Check
   → Research Agent
   → Verification Agent
        ↓
Gradio Web Interface Output
```

---

## 🛠️ Tech Stack

### AI / ML

* LangGraph (multi-agent orchestration)
* LangChain (RAG utilities)
* IBM WatsonX AI foundation models
* Embedding models for semantic search

### Data & Retrieval

* Docling document parser
* ChromaDB vector database
* BM25 lexical retrieval

### Application Layer

* Python
* Gradio UI
* Logging & caching pipeline

---

## ⚙️ Installation

```bash
git clone https://github.com/dystinktbeatz/multi-agent-rag-docchat.git
cd multi-agent-rag-docchat

python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

pip install -r requirements.txt
```

Run the app:

```bash
python app.py
```

Open:

```
http://127.0.0.1:5000
```

---

## 🧪 Usage

1️⃣ Upload one or more documents
2️⃣ Enter your question
3️⃣ Submit query
4️⃣ Receive:

* AI-generated answer
* Verification report
* Context-grounded explanation

---

## 📌 Project Note

This project was completed as part of the **IBM RAG & Agentic AI course**.

The original course material belongs to **IBM Developer Skills Network**.
This repository showcases **my personal implementation, experimentation, and learning based on that coursework.**

---

## 📈 Potential Enhancements

* Conversational memory support
* Document citation highlighting
* Advanced re-ranking models
* Cloud deployment (AWS / HuggingFace Spaces)
* Improved UI/UX
* Automated evaluation metrics

---

## 💼 Portfolio Value

This project demonstrates:

* Multi-agent AI system design
* Production-style RAG architecture
* Vector database integration
* Hybrid search implementation
* LLM orchestration & guardrails
* AI application deployment basics

---

## 🙏 Acknowledgements

* IBM Developer Skills Network
* WatsonX AI platform
* Open-source AI ecosystem contributors

---

⭐ If you find this useful, consider starring the repo!
