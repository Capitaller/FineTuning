# FineTuning Project

This repository contains the fine-tuning workflow and dataset preparation scripts for training AI models. It processes markdown files extracted from various books and synthesizes them into a unified dataset for model instruction and text generation tasks.

## Dataset

The model in this project was fine-tuned using a dataset compiled from the following books:

- Agentic AI Frameworks
- Architecting AI Software Systems
- Bedrock Agent Core Developer Guide
- Building Applications with AI Agents: Designing and Implementing Multi-Agent Systems
- Generative AI Design Patterns

## Codebase

- `books_combined_dataset.csv`: The exported dataset created from compiling the markdown texts. Ready for use with HuggingFace datasets library.
- `gemma4-E2B-architect.ipynb`: The main notebook containing the actual fine-tuning process.
