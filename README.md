# Multi-Modal Financial Analyst Agent

This project is a production-style Generative AI system that combines:

- SQL querying over structured financial data
- RAG over financial PDF reports
- LangGraph agentic workflow
- Qdrant vector database
- FastAPI REST endpoint
- Docker and Cloud Run deployment
- FinOps token cost tracking

## Project Architecture

User Question → FastAPI → LangGraph Agent → SQL Tool + Vector Search Tool → Final Answer

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
lien chatgpt:
https://chatgpt.com/share/6a2b18f8-8cf0-83ea-af41-a8ba66b768d5