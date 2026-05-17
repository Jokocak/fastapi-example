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
