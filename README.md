# LangChain Documentation Chatbot

A Streamlit-based chatbot that allows users to query LangChain documentation using RAG (Retrieval-Augmented Generation).

## Features

- 🔍 Semantic search through LangChain Python documentation
- 💬 Interactive chat interface with conversation history
- 📚 Source citations for transparency
- 🧠 Powered by OpenAI and Pinecone vector store

## Quick Start

```bash
# Activate virtual environment
source .venv/bin/activate

# Run the ingestion pipeline (first time only)
python ingestion.py

# Launch the chatbot
streamlit run main.py
```

## Tech Stack

- **LangChain**: Framework for LLM applications
- **Streamlit**: Web UI framework
- **Pinecone**: Vector database for document storage
- **OpenAI**: LLM for generating responses
- **Tavily**: Web crawling and content extraction

## Project Structure

- `ingestion.py`: Crawls and indexes LangChain documentation
- `main.py`: Streamlit chat interface
- `backend/core.py`: RAG chain logic
- `logger.py`: Custom logging utilities
