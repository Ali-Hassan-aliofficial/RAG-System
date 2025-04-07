# 🔍 RAG System - Retrieval-Augmented Generation using LangChain, FAISS, and HuggingFace

This project is an end-to-end implementation of a Retrieval-Augmented Generation (RAG) system. It combines the power of traditional document retrieval with advanced language generation using state-of-the-art models from Hugging Face.

RAG systems are ideal for:
- Knowledge-based Q&A systems
- Domain-specific search assistants
- Document-driven conversational agents
- Research summarizers and copilots

---

## 📌 Features

✅ Load and chunk raw text documents  
✅ Embed document chunks using `all-MiniLM-L6-v2`  
✅ Store and search embeddings with FAISS  
✅ Answer natural language questions with context-aware generation  
✅ Display source documents for transparency  

---

## 📁 Project Structure


---

## ⚙️ Requirements

- Python 3.8+
- Internet access (for Hugging Face models)

### 🔧 Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/rag-system.git
cd rag-system
Create a virtual environment
python -m venv venv
source venv/bin/activate       # Windows: venv\Scripts\activate


Install dependencies
pip install -r requirements.txt



Running the Project
Add your .txt files into the data/sample_docs/ folder.

Run the RAG pipeline
python src/rag_pipeline.py
sk your questions!

> What is retrieval-augmented generation?
The system will:

Retrieve the top-k relevant chunks using FAISS

Feed those into the LLM

Generate an accurate, grounded answer with references
