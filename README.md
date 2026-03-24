# LLM Engineering Projects

A hands-on learning repository covering **Large Language Model (LLM) engineering** — from foundational concepts to production-ready applications. Each project explores a different aspect of working with LLMs, building progressively from simple API calls to advanced RAG pipelines, fine-tuning, and deployment.

---

## Tech Stack

| Category | Tools |
|---|---|
| **LLM Providers** | OpenAI, Anthropic, Google Gemini, Ollama (local) |
| **Frameworks** | LangChain, Hugging Face Transformers, Gradio |
| **Vector Stores** | ChromaDB |
| **ML / Data** | PyTorch, scikit-learn, NumPy, Pandas |
| **Experiment Tracking** | Weights & Biases |
| **Deployment** | Modal |
| **Environment** | Python 3.11+, uv, Jupyter Notebooks |

---

## Projects

| # | Project | Description | Key Concepts |
|---|---------|-------------|--------------|
| 1 | **Movie Reviewer** | An AI movie critic that generates detailed reviews using OpenAI's chat completions API | Prompt engineering, system prompts, chat completions |
| | *More projects coming soon...* | | |

---

## Getting Started

### Prerequisites

- Python 3.11 or higher
- [uv](https://docs.astral.sh/uv/) package manager (recommended) or pip
- API keys for the LLM providers you want to use

### Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/LLM-Engineering-Projects.git
cd LLM-Engineering-Projects

# Create a virtual environment and install dependencies (using uv)
uv sync

# Or using pip
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

### Environment Variables

Create a `.env` file in the project root (never commit this file):

```bash
OPENAI_API_KEY=your-openai-key
ANTHROPIC_API_KEY=your-anthropic-key
GOOGLE_API_KEY=your-google-key
```

---

## Repository Structure

```
LLM-Engineering-Projects/
├── movie_reviewer.ipynb   # Project 1 — AI Movie Reviewer
├── pyproject.toml         # Project metadata & dependencies
├── requirements.txt       # Pip-compatible dependency list
├── .env                   # API keys (git-ignored)
└── README.md
```

---

## Learning Roadmap

```
Fundamentals                          Advanced
    │                                     │
    ▼                                     ▼
 Prompt Engineering ──► Chains & Agents ──► RAG Pipelines
    │                                         │
    ▼                                         ▼
 Chat Completions ──► Fine-Tuning ──► Deployment & Scaling
```

**Topics covered (and planned):**

- Prompt engineering & system prompt design
- Chat completions with multiple LLM providers
- LangChain chains, agents, and tools
- Retrieval-Augmented Generation (RAG) with vector stores
- Text embeddings and semantic search
- Model fine-tuning with Hugging Face
- Building interactive UIs with Gradio
- Experiment tracking with W&B
- Serverless deployment with Modal

---

## Contributing

This is a personal learning repository, but suggestions are welcome! Feel free to open an issue or submit a pull request if you spot improvements.

---

## License

This project is for educational purposes. See individual project notebooks for any specific licensing notes.
