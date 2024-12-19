# Q&A Dataset Generation and Evaluation

Capstone Project for the couse "Topics in Data Science" in WS 2024/25.

Contributers: Philipp Landeck, Annelie Friedl & Sebastian Leipold.

## Overview

This project involves creating and evaluating a Question & Answering (Q&A) dataset based on questionnaires provided by snapADDY. Key tasks include dataset generation, model evaluation using pre-trained Q&A models, and documentation.

## Main Tasks

1. **Generate Q&A Dataset**

   - Use techniques like:
     - Chatbots (e.g., ChatGPT) or APIs (e.g., HuggingFace).
     - Deep learning models (RoBERTa, DistilBERT).
     - Large language models (LLaMa, Gemini).
     - Fine-tuning a model to expand the dataset.

2. **Evaluate Dataset**
   - Assess dataset quality with pre-trained Q&A models.
   - Use different models for data generation and evaluation.
   - Explore metrics and evaluation strategies from the literature.

## Repository Structure

- [Questionnaires Folder](./questionnaires/) - Contains the provided questionnaires.
- [Userdata Folder](./userdata/) - Contains the generated data, which simmulates user input by speech.
- [Notebook Folder](./notebooks/) - Contains Jupyter notebooks for code and analysis.
- [QA Dataset File](./qa_dataset.json) - Contains expanded dataset including questions and answers. Basically the output of Task 1.
