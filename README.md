# AI Tool Hub + Portfolio Chatbot

A modern FastAPI backend that powers an intelligent chatbot on my personal portfolio website. Visitors can ask anything about my background and experience while also using practical MCP tools.

## Short Description

This project combines a **FastAPI + FastMCP** backend with Retrieval-Augmented Generation (RAG) to create a smart chatbot. The chatbot is embedded directly into my portfolio page, allowing users to:

- Ask questions about my Wells Fargo experience, skills, projects, and background
- Use various AI-powered tools through FastMCP

## Technologies / Tools Used

- **FastAPI** - Main web framework
- **FastMCP** - Model Context Protocol for AI tool integration
- **RAG (Retrieval-Augmented Generation)** - For answering questions about me using my resume and project data
- **Docker** - Containerization
- **GitHub Actions** - CI pipeline (linting, testing, Docker build)
- **Python 3.11+**
- **Groq** (primary LLM) - Fast and free-tier inference
- **ChromaDB / FAISS** - Vector store for RAG
- **Pytest + Ruff + Black** - Testing and code quality

## Features

- **Portfolio Chatbot** – Embedded on my personal website
- **Personal RAG Assistant** – Accurately answers questions about my experience and projects
- **Live MCP Tools** – Chatbot can call practical tools (data processing, APIs, etc.)
- **Streaming responses** for smooth user experience
- **Production-ready setup** with Docker and CI/CD

## How to Use

### Running Locally

```bash
# Clone the repository
git clone <your-repo-url>
cd ai-tool-hub

# Using Docker (Recommended)
docker compose up --build
```

API will be available at http://localhost:8000
Chatbot endpoint: POST /chat
Swagger UI: http://localhost:8000/docs

## Portfolio Integration
The FastAPI + FastMCP backend is deployed and connected to my portfolio website. The chatbot can be accessed directly on my portfolio page where it combines:

- My personal information (via RAG)
- Live tool usage through FastMCP

Live Demo: [Link to your portfolio page with chatbot]

## Project Purpose
This project serves as both a demonstration of my technical skills and an interactive way for recruiters and hiring managers to learn about my background and capabilities.
