# PrivacyBot: Using LLM-Powered RAG Pipelines to Improve Answer Quality Across Complex Privacy Policies

## 🧐 Overview
PrivacyBot is a state-of-the-art system designed to explore and evaluate different Retrieval-Augmented Generation (RAG) techniques. It uses LlamaIndex as its core framework to optimize interactions between large language models (LLMs) and data. The project focuses on enhancing user privacy literacy through conversational AI. This repository includes the implementation and evaluation of various RAG pipelines, from a basic Naive RAG model to more advanced techniques like Sentence Window Retrieval, Auto-Merging Retrieval, Re-ranking, and Prompt Engineering.

## 💡 Features
* **Naive RAG Implementation** : A baseline model that combines retrieval and generation.
* **Advanced RAG Techniques** : Includes Sentence Window Retrieval, Auto-Merging Retrieval, Re-ranking, and Prompt Engineering.
* **TruLens Evaluation** : Integration with TruLens framework for detailed evaluation metrics.
* **Configurable Pipelines** : Easily switch between different RAG pipelines.

## ⚙️ Setup
### Requirements
* Python 3.8 or above
* OpenAI API Key for LLM integration
* Required Python libraries are listed in requirements.txt.

## 📁 Folder Structure
* **src** : Contains the implementation and evaluation of all RAG pipelines in the files ragpipelines.py, app.ipynb, and evaluation.ipynb.
* **files** : Contains the files needed for the training and evaluation of the RAG pipelines.
* **config.yaml** : Configuration file for setting up API keys and models.
* **requirements.txt** : List of required Python libraries.

## 👩‍💻 Usage
1. **Running the Pipelines** :
   * You can run the RAG pipelines using the notebook app.ipynb and the Python file ragpipelines.py.
   * Select the desired pipeline and run queries to get responses.

2. **Evaluating Pipelines** :
   * The evaluation is conducted through the evaluation.ipynb notebook.
   * Metrics such as Answer Relevance, Context Relevance, Groundedness, Latency, Cost of API calls, and Token Consumption are computed using TruLens.

## 🤖 RAG Pipelines & Enhancing Techniques
* **Naive RAG Pipeline**
* **Sentence Window Retrieval**
* **Auto-merging Retrieval**
* **Re-ranking**
* **Prompt Engineering**

## 🎯 Evaluation and Results
The evaluation is conducted using TruLens, an evaluation framework that uses LLM Evals and feedback functions. The results highlight the strengths and weaknesses of each pipeline, focusing on the following performance metrics; Context Relevance, Groundedness, and Answer Relevance, and the following efficiency metrics; token consumption, latency, and cost of API calls.
