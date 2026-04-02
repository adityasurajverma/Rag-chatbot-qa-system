# Rag-chatbot-qa-system
# 🤖 RAG-Based Chatbot using FAISS and Sentence Transformers

## 📌 Project Overview
This project is a production-level AI chatbot built using Retrieval-Augmented Generation (RAG) architecture. It leverages semantic search to provide accurate answers from a dataset of 15,000+ question-answer pairs.

## 🚀 Features
- Semantic search using FAISS vector database
- Embeddings using Sentence Transformers
- Handles 15K+ Q&A dataset efficiently
- Similarity threshold to avoid incorrect responses
- Real-time chatbot interaction
- Fully built using free and open-source tools

## 🧠 Tech Stack
- Python
- Pandas
- FAISS
- Sentence Transformers
- LangChain
- FastAPI / Streamlit (optional)

## ⚙️ How It Works
1. Convert questions into embeddings
2. Store embeddings in FAISS vector database
3. User query is converted into embedding
4. Retrieve top similar questions
5. Return the most relevant answer

## 📂 Dataset
- CSV file with 24,000+ question-answer pairs

## 🛠️ Setup Instructions
```bash
