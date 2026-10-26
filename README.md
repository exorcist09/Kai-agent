# KAI - AI Agent 
KAI is the AI agent service for **Kairo**, a visual workflow automation and job scheduling platform. It is built as a separate Python microservice to provide AI-powered workflow assistance and intelligent automation.

## Tech Stack

- **Python** — Core language
- **FastAPI** — REST API
- **LangChain** — LLM integration and tool calling
- **LangGraph** — Agent workflows and orchestration
- **Hugging Face** — Models and embeddings
- **Weaviate** — Vector database for knowledge retrieval

## Architecture

KAI runs independently from Kairo and communicates with its Node.js/Express backend through APIs.

- **Kairo:** Workflow builder, authentication, scheduling, and execution.
- **KAI:** AI reasoning, workflow assistance, and agent orchestration.

## Getting Started

```bash
# Install uv if needed

# Install dependencies
uv sync

# Start the development server
uv run uvicorn app.main:app --reload
```

API documentation: `http://127.0.0.1:8000/docs`


## Status

Under active development.
