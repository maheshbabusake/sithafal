# sithafal

# Chat with PDFs Using RAG Pipeline

This repository contains a Streamlit application that allows users to interact with PDF documents using a Retrieval-Augmented Generation (RAG) pipeline. The system processes PDF files, stores embeddings in a FAISS vector database, and provides answers to user queries based on the document content.

---

## Features

- **PDF Processing**: Extracts text from uploaded PDF files.
- **Chunking for Efficient Processing**: Splits text into manageable chunks for embedding.
- **Embeddings Storage**: Uses FAISS for storing and retrieving vector embeddings.
- **Question-Answering**: Retrieves relevant content to answer user queries about the PDFs.
- **User-Friendly Interface**: Built with Streamlit for easy interaction.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chat-with-pdfs.git
   cd chat-with-pdfs
