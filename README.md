# AI Tool Hub API

A modern FastAPI backend that provides practical AI-powered tools through FastMCP (Model Context Protocol). 

This project demonstrates production-ready practices for building, containerizing, and testing backend services.

## Short Description

A lightweight REST API built with FastAPI that exposes several useful tools and AI capabilities via FastMCP. The service is fully containerized with Docker and includes CI pipelines using GitHub Actions.

## Technologies / Tools Used

- **FastAPI** - Main web framework
- **FastMCP** - Model Context Protocol for AI tool integration
- **Docker** - Containerization
- **GitHub Actions** - CI pipeline (linting, testing, Docker build)
- **Python 3.11+**
- **Pytest** - Testing
- **Ruff + Black** - Code formatting and linting

## How to Use

### Prerequisites
- Docker and Docker Compose (recommended)
- Python 3.11+ (for local development)

### Running with Docker (Recommended)

```bash
# Clone the repository
git clone <your-repo-url>
cd ai-tool-hub

# Build and run the container
docker compose up --build
