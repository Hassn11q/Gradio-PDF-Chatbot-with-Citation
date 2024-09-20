# DSPY Chatbot

## Description

chatbot leverages embeddings, document loading, and retrieval systems to provide accurate responses supported by citations from provided documents.

## Features

- Chatbot interface powered by Gradio
- Document processing using Langchain
- Semantic chunking for improved understanding
- Integration with Qdrant for vector storage and retrieval
- Supports PDF document ingestion

## Requirements

This project requires the following Python packages:

- `gradio`
- `python-dotenv`
- `langchain-experimental`
- `langchain-cohere`
- `langchain-community`
- `qdrant-client`
- `dspy`

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
