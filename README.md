# RetrievalAugmentedGeneration-Tutorial
Starter Guide for RAG (Retrieval Augmented Generation) using local models with Ollama and Chroma. 

This Jupyter Notebook guides you through building a Retrieval Augmented Generation (RAG) pipeline using **Chroma** for vector storage and **Ollama** for embeddings + LLM generation.

## Expected Data-Structure
```csv
TicketId,Project,Question,Answer
1001,CRM Suite,Cannot log into the CRM; getting 'invalid credentials' even though my password is correct.,"We reset the user's password, cleared browser cache, and verified SSO token freshness. Issue resolved."
```

## Prerequisites
- Install & run **Ollama**: `ollama serve` and pull models (e.g., `ollama pull llama3.1`, `ollama pull nomic-embed-text`).
- Install Python packages: `pip install chromadb pandas ollama`.
- Place your CSV file (e.g., `tickets.csv`) in the same working directory as this notebook.
