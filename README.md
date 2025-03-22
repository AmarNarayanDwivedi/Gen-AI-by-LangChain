# Langchain Practice Repository

This repository contains my practice files and code related to learning and working with Langchain. Throughout this project, I have explored and implemented various components, modules, and techniques. The main topics covered include:

- **Basic Components and Modules in Langchain**
- **Data Ingestion with Documents Loaders**
- **Text Splitting Techniques**
  - Recursive Character Text Splitter
  - Character Text Splitter
  - HTML Header Text Splitter
  - Recursive JSON Splitter
- **OpenAI Embeddings**
- **Ollama Embeddings**
- **Huggingface Embeddings**
- **Vector Stores** 
  - FAISS
  - ChromaDB

## Introduction

This repository contains files and code examples that demonstrate my understanding and practice of Langchain components, text splitting techniques, and various embedding methods such as OpenAI, Ollama, and Huggingface embeddings. The goal is to showcase how to ingest data, manipulate text, and store vectors in different vector stores.

## Technologies Used

- Langchain
- OpenAI API
- Ollama API
- Huggingface Transformers
- FAISS
- ChromaDB

## Setup and Installation

Follow these steps to set up the project and run the code:

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/langchain-practice.git
   ```
   
2. **install dependencies Create a virtual environment (optional but recommended) and install the required libraries.**

 ```bash

python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
pip install -r requirements.txt
 ```

3.**Set up API keys Some of the modules, such as OpenAI and Ollama, require API keys. Please set them as environment variables or create a .env file in the root directory and add the necessary keys:**

 ```bash
OPENAI_API_KEY=your-openai-api-key
OLLAMA_API_KEY=your-ollama-api-key
```

