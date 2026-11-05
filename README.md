PDF-BASED RAG CHATBOT
Using Python, Groq API & ChromaDB

==================================================

1. PROJECT OVERVIEW

This project is an AI-powered Retrieval-Augmented Generation (RAG) chatbot that allows users to ask questions about PDF documents.

It extracts text from PDF files, divides the text into smaller chunks, generates embeddings, and stores them in ChromaDB. When a user asks a question, the chatbot retrieves relevant information and uses the Groq API to generate an answer based on the uploaded documents.

2. KEY FEATURES

- Extract text from multiple PDF documents.
- Clean and split extracted text into smaller chunks.
- Generate embeddings for document chunks.
- Store document chunks in ChromaDB.
- Retrieve relevant information using similarity search.
- Generate AI-powered answers using Groq API.
- Maintain chat history during conversations.
- Display document sources and page numbers.

3. TECHNOLOGIES USED

Python: Main programming language.
Groq API: Generates AI-powered responses.
ChromaDB: Stores and retrieves document embeddings.
PyPDF: Extracts text from PDF documents.
Embedding Function: Converts text into numerical vectors.
Google Colab: Development environment.

4. PROJECT WORKFLOW

1. Upload PDF documents into the docs folder.
2. Extract text from PDF files.
3. Clean the extracted text.
4. Divide text into smaller chunks.
5. Generate embeddings for each chunk.
6. Store chunks and metadata in ChromaDB.
7. Retrieve relevant chunks according to the user's question.
8. Send retrieved context to the Groq API.
9. Generate and display the final answer with sources.

5. PROJECT STRUCTURE

RAG-Chatbot/
    |
    |---- docs/
    |       |---- sample.pdf
    |
    |---- RAG_Chatbot.ipynb
    |
    |---- README.txt
    |
    |---- requirements.txt

6. INSTALLATION

Install the required Python libraries:

pip install groq chromadb pypdf

7. API CONFIGURATION

This project uses the Groq API to generate AI responses.

8. EXAMPLE USE CASE

User Question:
What are the main topics discussed in the uploaded PDF?

Chatbot Response:
The chatbot retrieves relevant information from the PDF and generates an answer using the Groq API.

9. LEARNING OUTCOMES

Through this project, I practiced:

- Working with external APIs.
- PDF text extraction.
- Text preprocessing and chunking.
- Embeddings and vector databases.
- Semantic search and information retrieval.
- Retrieval-Augmented Generation (RAG).
- Building AI-powered conversational applications.

10. AUTHOR

Developed as a Python and AI learning project.
