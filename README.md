# RAG with LangGraph

A Retrieval-Augmented Generation (RAG) system built with LangGraph and LangChain.

## Setup

You're using Anaconda Python, so the packages are already installed! If you need to reinstall:

```bash
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file in the project root:

```
OPENAI_API_KEY=your_api_key_here
```

## Usage

Open and run the Jupyter notebooks:

- `RAGWithLangraph.ipynb` - Main RAG implementation with LangGraph
- `typesense.ipynb` - Typesense integration
- `Mongo.ipynb` - MongoDB integration

## Project Structure

```
RAG/
├── RAGWithLangraph.ipynb  # Main RAG implementation
├── typesense.ipynb        # Typesense examples
├── Mongo.ipynb            # MongoDB examples
├── books.jsonl            # Sample data
├── test.txt               # Test data
├── requirements.txt       # Python dependencies
└── README.md              # This file
```

## Features

- **Agentic RAG**: Uses LangGraph for stateful multi-step reasoning
- **Vector Search**: FAISS for efficient similarity search
- **OpenAI Integration**: GPT-4 for generation with embeddings
- **Conditional Retrieval**: Intelligent decision on when to retrieve documents
