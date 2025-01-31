# job_coverletter_gen

Generate tailored job cover letters based on your CV (PDF) context and a given job description using a locally running LLM instance.

## Setup

1. **Install Ollama:** Download and install Ollama locally from [https://ollama.com](https://ollama.com).

1. **Pull models:** Pull the required models from Ollama using the following command:
   ```bash
   ollama pull llama3.2
   ```

1. **Install uv:** Install uv for dependency management: `pip install uv`

1. **Create Virtual Environment:**
   ```bash
   uv sync
   source .venv/bin/activate
   ```
