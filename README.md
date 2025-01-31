# Q&A Dataset Generation and Evaluation
Capstone Project for the couse "Topics in Data Science" in WS 2024/25.

**Contributors**: Philipp Landeck, Annelie Friedl & Sebastian Leipold.

## Overview
This project involves creating and evaluating a Question & Answering (Q&A) dataset based on questionnaires provided by snapADDY. Key tasks include dataset generation, model evaluation and the development of a dashboard.

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

## Dashboard  
The dashboard serves as an interactive application for working with the provided questionnaires. It allows users to process questionnaires efficiently through a structured interface with dropdowns, buttons, a chat window, and speech-to-text input. Users can interact with the system, receive responses, and download completed questionnaires. The application was developed using Gradio, incorporating both frontend and backend components to ensure smooth usability.

![Dashboard Preview](https://raw.githubusercontent.com/croco22/CapstoneProjectTDS/refs/heads/main/images/screenshot20.png)

## Repository Structure
- [`images`](https://github.com/croco22/CapstoneProjectTDS/tree/main/images) - Contains image files for documentation.
- [`notebooks`](https://github.com/croco22/CapstoneProjectTDS/tree/main/notebooks) - Includes Jupyter notebooks for code and analysis.
- [`questionnaires`](https://github.com/croco22/CapstoneProjectTDS/tree/main/questionnaires) - Stores the provided questionnaires.
- [`userdata`](https://github.com/croco22/CapstoneProjectTDS/tree/main/userdata) - Contains initial data generated to simulate user input via speech (no longer in use).
- [`qa_dataset.json`](https://github.com/croco22/CapstoneProjectTDS/blob/main/qa_dataset.json) - The expanded dataset including questions and answers.

---

&copy; February 2025
