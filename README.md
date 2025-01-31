# job_coverletter_gen

Generate tailored job cover letters based on your CV (PDF) and a job description using a locally running LLM.

## Setup

1. **Install Ollama:** Download and install Ollama from [https://ollama.com](https://ollama.com).

1. **Download Models:** Pull the `llama3.2` model (or another suitable model):

   ```bash
   ollama pull llama3.2
   ```

1. **Install uv:** Install uv for dependency management: `pip install uv`

1. **Create Virtual Environment:**
   ```bash
   uv sync
   source .venv/bin/activate
   ```

## Usage

The generated cover letter will be printed to the notebook space as you run the cell in the notebook. You can then copy and paste it into your preferred document editor.


###  Adding New Models

To use a different model, pull it using `ollama pull <model_name>` and update the model name in the notebook `job_coverletter_gen.ipynb`.


## Contributing

Contributions are welcome!  Please open an issue or submit a pull request.