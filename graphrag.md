# GraphRAG Knowledge Orchestrator

## Overview
This GraphRAG Knowledge Orchestrator is an AI system that combines retrieval-augmented generation (RAG) with a knowledge graph backbone to deliver transparent, verifiable answers. By blending graph search, vector embeddings, and LLM reasoning, it allows users to explore relationships across entities, trace evidence paths, and summarize context with citations.

The orchestrator is designed for cost-aware, modular AI workflows, offering observability on latency and token usage while ensuring results remain explainable and auditable. This makes it a powerful foundation for domains where trust, transparency, and efficiency are critical.  

## Example Use Cases
- Trace relationships between entities in a knowledge graph.  
- Answer “What events connect X and Y?” with supporting evidence paths.  
- Summarize context across documents with citations.  
- Compare how multiple sources describe the same entity.  

## Architecture Diagram
![Architecture Diagram](images/graphrag_architecture.png)  

## Sequence Diagram
![Sequence Diagram](images/graphrag_sequence.png)  

## Key Highlights
- 🔎 Graph-based retrieval with **NetworkX** + **ChromaDB** + **SQLite**.  
- ⚡ Confidence feedback loop with re-prompting for low-confidence answers.  
- 🤖 LLM orchestration with **OpenAI APIs** (embeddings + generation).  
- 📊 Observability: latency, token usage, and cost tracking.  
- 🧩 Modular design: UI, router, orchestrator, retrieval hub, external LLMs.  

## Tools & Frameworks
- **Python**  
- **NetworkX** (graph structure + path search)  
- **ChromaDB** (vector store for embeddings)  
- **SQLite** (document storage)  
- **OpenAI APIs** (embeddings + generation)  
- **pandas / sklearn** (lightweight analytics + evaluation)  

---

[⬅ Back to Portfolio Home](README.md)
