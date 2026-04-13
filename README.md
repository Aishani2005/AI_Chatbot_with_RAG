# 🤖 AI Chatbot with RAG

An AI-powered chatbot that answers questions from PDF documents
using Retrieval Augmented Generation (RAG) architecture.

## 🚀 What it Does
Upload any PDF and ask questions — the chatbot finds relevant 
content and gives accurate AI-powered answers!

## 🛠️ Tech Stack
- **Python** — Core language
- **ChromaDB** — Vector database for semantic search
- **Groq LLaMA 3.1** — Fast AI language model
- **PyMuPDF** — PDF text extraction
- **Google Colab** — Development environment

## 📋 How It Works
1. Upload any PDF document
2. Text is extracted and split into chunks
3. Chunks are embedded and stored in ChromaDB
4. User question is matched to relevant chunks
5. Groq LLaMA generates answer from matched context

## 🏃 How to Run
1. Open the `.ipynb` file in Google Colab
2. Run Cell 1 and restart runtime
3. Run cells 2 to 8 in order
4. Get free Groq API key from console.groq.com
5. Start asking questions!

## 📦 Libraries Used
- chromadb
- pymupdf
- groq

## 👩‍💻 Author
Aishani — [GitHub](https://github.com/Aishani2005)
