# 🧠 Personality Type Classification via Text Analysis (MBTI-based)

![Python](https://img.shields.io/badge/Python-3.11-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-orange.svg)
![NLP](https://img.shields.io/badge/NLP-Text%20Processing-green.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red.svg)

## 📌 Project Overview
This Machine Learning project focuses on predicting human personality types based on textual data. Inspired by the Myers-Briggs Type Indicator (MBTI) framework, the model leverages Natural Language Processing (NLP) techniques to analyze linguistic patterns and classify users into one of **6 distinct personality types**.

This repository demonstrates a complete ML pipeline, from raw text preprocessing and feature engineering to model training, evaluation, and business storytelling.

## 🎯 Objectives
* Extract meaningful linguistic features from unstructured textual data.
* Build and train a robust Machine Learning classifier to predict personality types.
* Evaluate model performance using appropriate metrics (Accuracy, Precision, Recall, F1-Score).
* Translate technical findings into human-centric psychological insights (detailed in the presentation).

## 🛠️ Methodology & NLP Pipeline
1. **Text Preprocessing:** * Removing noise (URLs, special characters, numbers).
   * Tokenization, Stop-word removal, and Lemmatization/Stemming to standardize the vocabulary.
2. **Feature Extraction:** * Converting textual data into numerical vectors using techniques such as **TF-IDF** (Term Frequency-Inverse Document Frequency) or Word Embeddings to capture semantic meaning.
3. **Model Training:** * Applying robust classification algorithms tailored for high-dimensional text data to identify the 6 target personality clusters.
4. **Evaluation:** * Analyzing the confusion matrix and classification reports to ensure balanced detection across different personality classes.

## 📊 Insights & Presentation
The technical implementation is paired with a comprehensive presentation (`pdf_project_ML_Hassan_Alomari.pdf`) that bridges the gap between data science and behavioral psychology. It covers the problem statement, data distribution, model selection rationale, and final conclusions.

## 📂 Repository Structure
For a clean and professional setup, the repository is organized as follows:

```text
├── notebooks/
│   └── project_ML_Hassan_Alomari.ipynb    # Main notebook containing the NLP pipeline and ML models
├── presentations/
│   └── pdf_project_ML_Hassan_Alomari.pdf  # Project slides and insights
└── README.md                              # Project documentation
