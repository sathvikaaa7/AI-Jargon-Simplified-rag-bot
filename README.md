# RAG

This project implements Retrieval-Augmented Generation (RAG) for enhanced AI responses.

## Features

- Retrieval from knowledge base
- Generation of context-aware answers

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/RAG.git
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt

3. Environment Variables

Create a .env file in the project root:

GOOGLE_API_KEY=your_api_key_here
Run the Project
python main.py


## INTRO

A Retrieval-Augmented Generation (RAG) application built using LangChain and Google Gemini. This project allows users to ask questions based on custom PDF documents and receive context-aware AI-generated answers.

The project currently uses my own AI learning blog series content (exported as PDF) and a research Paper on Langchain as the knowledge base for retrieval and response generation.

### Features:
PDF document loading

Text chunking and preprocessing

Embedding generation

Vector database retrieval

Context-aware AI responses

Google Gemini integration

LangChain-based RAG pipeline


### Tech Stack
Python
LangChain
Google Gemini API
ChromaDB
Sentence Transformers
PyPDF / PyMuPDF

### Working
PDF documents are loaded into the system.
The text is split into smaller chunks.
Embeddings are generated for each chunk.
Embeddings are stored in a vector database.
Relevant chunks are retrieved based on the user query.
Retrieved context is passed to Gemini for response generation.

### Future Improvements
Streamlit UI integration
Multiple file support
Chat history and memory
Source citation display
Improved prompt engineering

### Learning Outcome

This project was built while learning about:

Retrieval-Augmented Generation (RAG)
LangChain
Vector databases
Embeddings
Google Gemini API integration
AI application development

## Contributing

Feel free to submit issues and pull requests.
