# AI Sales Brochure Generator

An automated AI tool designed to analyze company information and generate structured, professional sales brochures using LLMs. Built with Python, managed via `uv`, and designed to integrate with local models (Ollama) and OpenAI APIs.

---

## Overview

The **Sales Brochure Generator** extracts relevant business insights from input data (or website content) and produces marketing assets through a pipeline of LLM calls. It demonstrates practical LLM engineering patterns such as structured outputs, prompt chaining, and real-time response streaming.

---

## Key Features

- **Local & Cloud LLM Support:** Compatible with local models via Ollama (e.g., Llama 3) as well as OpenAI's Chat Completions API.
- **Structured Data Extraction:** Uses JSON schemas and Pydantic to ensure reliable and strictly formatted outputs.
- **Prompt Chaining:** Breaks down complex content generation into sequential, modular LLM tasks.
- **Real-time Streaming:** Delivers low-latency user experiences by streaming responses token by token.

---



## Tech Stack & Tooling

- **Language:** Python 3.11+
- **Package Management:** [uv](https://github.com/astral-sh/uv)
- **LLM Backends:** Ollama (Local) / OpenAI API
- **Libraries:** `openai`, `ollama`, `pydantic`, `python-dotenv`

---



## Project Structure

```text
.
├── src/
│   └── llms_course/       # Core application source code
├── .env.example           # Template for environment variables
├── .gitignore             # Git ignore rules for security and cache
├── pyproject.toml         # Project dependencies and configuration
├── uv.lock                # Deterministic dependency lockfile
└── README.md              # Project documentation
```

