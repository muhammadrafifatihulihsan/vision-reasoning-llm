# Vision Reasoning LLM (Large Language Model)

Vision Reasoning LLM is an experimental Vision Language Model (VLM) project built using local multimodal Large Language Models. This project explores how vision-enabled LLMs can understand images, generate captions, answer questions, perform scene analysis, and reason about visual content.

The project uses Qwen vision models running locally through Ollama and focuses on multimodal reasoning experiments inside Jupyter Notebook environments.

## Features

- Image caption generation
- Scene understanding
- Visual question answering (VQA)
- Image reasoning experiments
- Structured output generation
- Local inference using Ollama
- Notebook based experimentation

## Project Goals

This project aims to explore:

- Vision Language Models (VLM)
- Multimodal prompting
- Image understanding pipelines
- Local multimodal inference
- AI experimentation workflows

## Tech Stack

- Python
- Jupyter Notebook
- Ollama
- Qwen Vision Models
- Requests
- Pillow
- Matplotlib
- Pandas

## Project Structure

```text
vision-reasoning-llm/
|
|-- notebooks/
|-- images/
|-- outputs/
|-- requirements.txt
|-- README.md
```

## Installation

Clone repository:

```bash
git clone https://github.com/muhammadrafifatihulihsan/vision-reasoning-llm.git
cd vision-reasoning-llm
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Pull Qwen model:

```bash
ollama pull qwen3.5:4b
```

Run Ollama:

```bash
ollama serve
```

Launch notebook:

```bash
jupyter notebook
```

## Example Workflow

Input image:

```text
Image
↓
Qwen Vision Model
↓
Caption
↓
Scene Understanding
↓
Visual Question Answering
↓
Reasoning Output
```

Example prompt:

```python
result = ask_qwen_image(
    "sample1.jpg",
    "Describe this image briefly."
)
print(result)
```

## Current Experiments

- Caption generation
- Scene understanding
- Visual reasoning
- Structured outputs
- Batch image experiments

## Future Improvements

- Evaluation pipeline
- Dataset benchmarking
- Web interface
- RAG integration
- Agentic workflows

## Example Use Cases

- Image understanding
- Educational experiments
- Local multimodal inference
- AI portfolio projects
- Visual reasoning research

## Author

- [@muhammadrafifatihulihsan](https://github.com/muhammadrafifatihulihsan)
