# 📄 Ask Your PDF 💬

A Streamlit-powered question answering app that allows users to **upload a PDF** and **ask questions** about its content using OpenAI's GPT models and LangChain.

---

## 🚀 Features

- 📤 Upload any PDF file
- 📖 Extract text from the PDF
- 🧠 Create embeddings using OpenAI's embedding model
- 🔍 Perform similarity search using FAISS
- 🤖 Answer your questions using GPT (via LangChain QA chain)
- 📊 View OpenAI API usage with built-in callback logger

---

## 🛠️ Requirements

Install dependencies:

```bash
pip install streamlit python-dotenv PyPDF2 langchain openai faiss-cpu
