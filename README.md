# AI Rental Assistant (RAG + LLM Agent)

## Overview
This project is a conversational AI system designed for rental search. It uses Retrieval-Augmented Generation (RAG) and tool-calling to provide accurate and actionable responses based on user queries.

## Features
- Multi-turn dialogue system
- Retrieval-Augmented Generation using FAISS
- LLM-based tool calling for structured actions
- Location understanding and geospatial expansion
- Backend API orchestration for housing search

## Tech Stack
- Python
- OpenAI API
- FAISS
- Pandas / NumPy
- Geopy

## Architecture
1. User query is processed and analyzed
2. Relevant context is retrieved via vector search
3. LLM generates response with tool-calling if needed
4. Backend services execute structured actions

## Notes
This notebook demonstrates the core pipeline for embedding, retrieval, and response generation.

Due to API key expiration, this demo may not run directly. The repository focuses on system design and pipeline implementation.
