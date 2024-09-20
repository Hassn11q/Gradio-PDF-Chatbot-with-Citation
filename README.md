# PDF Chatbot with Citation

## Description

chatbot leverages embeddings, document loading, and retrieval systems to provide accurate responses supported by citations from provided documents.

## Features

- Chatbot interface powered by Gradio
- Document processing using Langchain
- Semantic chunking for improved understanding
- Integration with Qdrant for vector storage and retrieval
- Supports PDF document ingestion
- Powered by DSPy for retrieval-augmented generation


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
```

## Setup 
1- Clone the repository:

```bash
git clone https://github.com/Hassn11q/Gradio-Chatbot-using-DSPy-and-cohere.git
```
2 - Create a .env file in the root directory and add your API keys:
```bash
COHERE_API_KEY=your_cohere_api_key
```
You can obtain your Cohere API key from [Cohere Dasboard](https://dashboard.cohere.com/welcome/login)

3 - Place your PDF documents in the data folder.

## Usage 
To run the chatbot, open the Jupyter Notebook file app.ipynb and execute the cells. The Gradio interface will launch, allowing you to interact with the chatbot.

## Screenshot
![DSPY Chatbot Screenshot](./images/screenshot.png)
