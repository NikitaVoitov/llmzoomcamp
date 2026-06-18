# LLM Zoomcamp 2026

Homework and experiments for [LLM Zoomcamp](https://github.com/DataTalksClub/llm-zoomcamp) by DataTalks.Club.

Environment setup follows the course [Environment lesson](https://github.com/DataTalksClub/llm-zoomcamp/blob/main/01-agentic-rag/lessons/02-environment.md) (Python 3.14+, `uv`, Jupyter, dependencies via `pyproject.toml`).

## Setup

```bash
uv sync
cp .env.example .env
```

Fill in `.env` — we use [OpenRouter](https://openrouter.ai/) as an OpenAI-compatible provider:

| Variable | Description |
|----------|-------------|
| `OPENAI_API_KEY` | OpenRouter API key (`sk-or-v1-...`) |
| `OPENAI_BASE_URL` | `https://openrouter.ai/api/v1` |
| `OPENAI_MODEL` | Model ID, e.g. `openai/gpt-oss-120b:free` |

Then open `hw1.ipynb` or `test.ipynb`.
