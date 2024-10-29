# Fine-tune code-llama 7B to become SQL expert

This project involves fine-tuning the Code Llama model to become proficient in generating SQL queries from natural language questions. The project is organized into two main components: training the model and deploying it using Gradio for interactive use.

## Project structure

- **train.ipynb**: this Jupyter notebook contains the code for fine-tuning the Code Llama model using LoRA and a dataset of text-to-SQL examples.
- **deploy.ipynb**: this Jupyter notebook sets up a Gradio interface to interact with the fine-tuned model, allowing users to input context (e.g. database schemas) and questions to receive SQL query outputs.

## Setup instructions

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- Nvidia GPU
- Kaggle account (if running on Kaggle)
- Required Python packages:
  - `transformers`
  - `datasets`
  - `accelerate`
  - `gradio`
  - `torch`
  - `peft`
  - `bitsandbytes` (for model quantization)
  - `wandb` (for experiments tracking)
