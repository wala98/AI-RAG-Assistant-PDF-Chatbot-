# AI RAG Assistant (PDF Chatbot)

A powerful Retrieval-Augmented Generation (RAG) system that enables intelligent conversations with your PDF documents using LangChain and Gradio.

## 📋 Project Overview

This project implements a sophisticated RAG pipeline that allows users to upload PDF documents and ask questions about their content. The system processes documents, creates searchable vector stores, and leverages external Large Language Models (LLMs) to generate accurate, context-aware answers based exclusively on the uploaded files.

## ✨ Features

- **📄 PDF Document Ingestion**: Seamlessly loads and processes content from user-uploaded PDF files
- **🔍 Intelligent Text Processing**: Implements advanced chunking with overlapping for optimal text retrieval
- **🗄️ Vector Database (Chroma)**: Stores text embeddings for fast and relevant context retrieval
- **🤖 Custom LLM Integration**: Connects to powerful models via OpenRouter (Deepseek, Qwen, etc.)
- **🎨 Interactive Web UI**: User-friendly Gradio interface for easy interaction
- **🧠 Conversational Memory Ready**: Architecture designed for easy upgrade to support chat history
