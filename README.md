# LLMComparision
# Text Summarization Evaluation Project

## Overview

This project aims to evaluate the performance of various Open Large Language Models (OpenLLMs) in the context of text summarization. We have tested five models: GPT-3, ChatGPT 'gpt-3.5-turbo', Flan-20B, Flan-T5-XL, and Cohere-command-xl. The objective is to identify the most effective model for generating concise and informative text summaries.

## Approach

1. **Task Definition**: The project begins by defining the task of text summarization, where we aim to generate shorter summaries while retaining essential content from longer documents.

2. **Model Selection**: We selected five OpenLLMs for evaluation. The Langchain platform was used for testing and accessing these models.

3. **Data Preparation**: Diverse datasets, including news articles, academic papers, and other sources, were gathered to ensure comprehensive testing.

4. **Evaluation Metrics**: We employed standard text summarization evaluation metrics, including ROUGE, BLEU, and METEOR, to quantify the quality of the generated summaries.

5. **Testing Procedure**: For each model, we followed a consistent procedure:
   - Preprocessing the text data.
   - Inputting the data into the model.
   - Collecting and evaluating the generated summaries using the chosen metrics.

## Results

The performance of each model was compared based on the evaluation metrics. This allowed us to recommend the most effective model for text summarization.

## Usage

You can replicate this evaluation project using Langchain or other platforms that provide access to OpenLLMs. Be sure to adapt the model selection and data preparation steps to your specific needs.

