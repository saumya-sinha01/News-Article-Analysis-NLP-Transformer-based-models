# News Analysis and Text Prediction with Fine-Tuned Language Models

In today's fast-paced world, analyzing and predicting text data is a crucial aspect of Artificial Intelligence (AI). Modern research has led to the development of efficient and powerful Large Language Models (LLMs) capable of producing impressive results for various downstream tasks through fine-tuning.

## Project Overview

This project presents a comprehensive News Analysis system that leverages Natural Language Processing (NLP) and AI models to perform the following tasks on news articles and other text data:

- **Summarization**: Generate concise summaries of lengthy articles.
- **Classification**: Categorize articles into predefined categories.
- **Search**: Efficiently search for articles based on specific keywords or topics.
- **Named Entity Recognition (NER)**: Identify and extract important named entities such as people, organizations, and locations.

## Scope and Approach

The project focuses on fine-tuning pre-trained models from the Hugging Face repository on various NLP tasks, including:

- **Summarization**: Using the CNN/DailyMail dataset (1.29 GB).
- **Classification**: Utilizing the AG News and BBC News datasets (30 MB).
- **NER**: Leveraging the NER_dataset.

## Models and Performance

### Summarization:

- **Models**: Pegasus, T5, and LLaMA 2.
- **Best Performer**: Pegasus, with a ROUGE-1 score of 0.36.

### Classification:

- **Models**: BERT, RoBERTa, and GPT-2.
- **Best Performers**: GPT-2 and BERT, both achieving an accuracy of 93%.
- An underlying ElasticSearch mechanism was proposed based on BERT model outcomes.

### NER:

- **Model**: LLaMA 2.
- **Best Performer**: LLaMA 2, with an F1 score of 0.79.

## Deliverables

The project provides an in-depth analysis and comparison of multiple state-of-the-art LLMs. The deliverables include:

- A comprehensive final report.
- Presentation slides summarizing the project's findings.
- Source code for model fine-tuning.
- A user-facing software application.
- Fine-tuned models available to the public on Hugging Face and GitHub.

## User Interaction

The application allows users to:

- Obtain summaries, categories, and important entities from any text data.
- Search for news articles within specific categories.

## Applications and Use Cases

In a world inundated with text data, this project is invaluable for:

- **Sentiment Analysis**: Understand the emotional tone of text data.
- **Legal Document Analysis**: Quickly summarize and analyze job offer letters, leasing agreements, or terms and conditions.
- **Research Paper Summarization**: Condense scholarly articles for easier consumption.
- **Elastic Search leverage the vector search and emdebbing to provide recommendation based on nearest neighbour calculated.

By fine-tuning powerful LLMs, this project offers a robust tool for anyone needing to analyze and interpret large volumes of text quickly and efficiently.
