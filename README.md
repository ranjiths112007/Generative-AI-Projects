# Generative AI Projects

A collection of my **Generative AI coursework, experiments, and task submissions**, covering LLMs, text generation, summarization, image generation, image captioning, and basic AI safety techniques.

This repository follows my learning progression from using language models to understanding how generative AI systems are built, connected, and controlled.

## What I Worked On

| Task / Experiment | What it explores |
|---|---|
| **Task 1** | Introduction to Generative AI concepts and workflows |
| **Task 2** | Running an LLM locally with Ollama and Llama 3.2 |
| **Task 3** | Generative AI / LLM experimentation |
| **Task 4** | Text summarization using a pretrained transformer model |
| **Task 5** | Image generation with a Hugging Face GAN |
| **Task 6** | Image captioning with Salesforce BLIP |
| **Task 7** | Prompt guardrails and basic prompt-injection detection |

The repository also contains the original/experimental notebooks used while working through the coursework.

## Highlights

### Text Generation & LLMs
Exploring how large language models can generate useful text and how local inference works with **Ollama + Llama 3.2**.

### Text Summarization
Using **BART-large-CNN** to turn longer text into shorter summaries while keeping the important information.

### Image Generation
Experimenting with a Hugging Face GAN to understand how generative models can create images instead of simply classifying them.

### Image Captioning
Using **Salesforce BLIP** to connect vision and language — taking an image as input and generating a natural-language description.

### Prompt Guardrails
A simple guardrail layer checks user prompts for common prompt-injection or unsafe patterns before they are passed to an LLM.

## Tech Stack

**Python · Hugging Face Transformers · PyTorch · Ollama · Llama 3.2 · BART · BLIP · GANs · Generative AI**

## Repository Structure

```text
Generative-AI-Projects/
├── GenAI Task 1.ipynb
├── GenAI_Task2_Ollama_Llama3.2 (1).ipynb
├── GenAI--3.ipynb
├── GenAI_Task4_Text_Summarization.ipynb
├── GAN_Image_Generation_HuggingFace (1).ipynb
├── GenAI_Task6_Image_Captioning.ipynb
├── GenAI_Task7_Prompt_Guardrail.ipynb
└── README.md
```

## Running the Notebooks

Open the notebooks with **Jupyter Notebook, JupyterLab, or Google Colab** and install the dependencies required by the individual experiment.

For transformer-based notebooks, packages commonly include:

```bash
pip install torch transformers pillow requests
```

The Ollama experiment additionally requires a local Ollama installation and the model used by the notebook.

## What I Learned

Working through these tasks made one thing clear to me: **Generative AI is much bigger than just prompting a chatbot.** There is a whole stack underneath it — model inference, transformers, multimodal models, image generation, local LLMs, and safety mechanisms.

These experiments are my college coursework foundation for going deeper into **LLMs and Generative AI engineering**.

## Coursework

These notebooks are primarily maintained as **college task submissions and learning experiments**, while keeping the implementations understandable enough to revisit and improve later.

---

Built while learning GenAI — from generating text to giving machines a way to understand images.
