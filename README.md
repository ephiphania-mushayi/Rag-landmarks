# RAG System — World Landmarks

A Retrieval-Augmented Generation (RAG) system built from scratch in Python using ChromaDB, Sentence Transformers, and the Anthropic Claude API.

## What it does
- Stores facts about world landmarks as vector embeddings
- Retrieves the most relevant facts based on a user question
- Uses Claude to generate an answer from the retrieved facts

## Tools Used
- ChromaDB — vector database for storing and searching embeddings
- Sentence Transformers — converts text into vector embeddings
- Anthropic Claude API — generates answers from retrieved documents

## How to Run
1. Install libraries: pip install chromadb sentence-transformers anthropic
2. Add your Anthropic API key where it says "your-api-key-here"
3. Run all cells in Jupyter Notebook

## What I Learned
- What RAG is and how it works end to end
- How text gets converted into vectors (embeddings)
- How to search by meaning using ChromaDB
- How to connect Python to the Claude API
