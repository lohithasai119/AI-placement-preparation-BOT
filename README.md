# 🤖 AI Placement Preparation Assistant

An AI-powered placement preparation chatbot built using **Python, Streamlit, LangChain, FAISS, and Hugging Face Inference API**. The application uses **Retrieval-Augmented Generation (RAG)** to provide context-aware answers based on uploaded placement preparation materials and technical learning resources.

## 🚀 Project Overview

The AI Placement Preparation Assistant helps students prepare for technical interviews and campus placements by allowing them to upload PDF study materials and interact with an AI chatbot.

The system processes uploaded documents, generates semantic embeddings, stores them in a FAISS vector database, and retrieves relevant information to generate contextual responses using a Large Language Model (LLM).

## ✨ Key Features

- **PDF Document Upload:** Supports uploading multiple placement preparation PDF documents.
- **RAG Architecture:** Implements Retrieval-Augmented Generation for context-based question answering.
- **Semantic Search:** Retrieves relevant document chunks using vector similarity search.
- **Vector Database:** Uses FAISS for efficient storage and retrieval of document embeddings.
- **AI-Powered Responses:** Integrates Hugging Face Inference API with Qwen2.5-1.5B-Instruct.
- **Conversational Interface:** Provides an interactive chatbot experience using Streamlit.
- **Context-Aware Retrieval:** Generates responses using relevant information extracted from uploaded documents.
- **Error Handling:** Implements retry mechanisms for handling temporary AI API failures.

## 🛠️ Technology Stack

| Component | Technologies |
|---|---|
| Programming Language | Python |
| Frontend / UI | Streamlit |
| AI Model | Qwen2.5-1.5B-Instruct |
| AI Integration | Hugging Face Inference API |
| Framework | LangChain |
| Embeddings | Sentence Transformers |
| Embedding Model | all-MiniLM-L6-v2 |
| Vector Database | FAISS |
| PDF Processing | PyPDF |
| Configuration | Python Dotenv |

## ⚙️ RAG Workflow

1. Upload placement preparation PDF documents.
2. Extract textual content using PyPDF.
3. Split documents into smaller chunks using RecursiveCharacterTextSplitter.
4. Generate vector embeddings using Hugging Face Sentence Transformers.
5. Store embeddings in the FAISS vector database.
6. Retrieve the most relevant document chunks based on user queries.
7. Pass the retrieved context to the Qwen language model.
8. Generate context-aware responses through the chatbot interface.

## 🎯 Objective

To develop an AI-powered learning assistant that simplifies placement preparation by enabling students to interact with their own study materials and retrieve relevant technical information efficiently.

## 👩‍💻 Author

**Lohitha Sai**

GitHub: https://github.com/lohithasai119
