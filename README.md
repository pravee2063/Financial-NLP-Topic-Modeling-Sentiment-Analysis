# 📈 Financial News Topic Modeling and Sentiment Analysis using Machine Learning & Transformer Models

End-to-end NLP pipeline for **financial news topic modeling** and **sentiment analysis** using **TF-IDF**, **Word2Vec**, **LDA**, **Machine Learning**, and **RoBERTa**.

> **Academic Group Project** • Data Mining • South Asian University

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Technologies](#-technologies)
- [Models Implemented](#-models-implemented)
- [Repository Structure](#-repository-structure)
- [Installation](#️-installation)
- [Dataset](#-dataset)
- [Workflow](#-workflow)
- [Results](#-results)
- [Team](#-team)
- [My Contributions](#-my-contributions)
- [Future Work](#-future-work)
- [References](#-references)

---

## 📖 Overview

This project presents an end-to-end Natural Language Processing (NLP) pipeline for analyzing financial news headlines through **Topic Modeling** and **Sentiment Analysis**.

The project combines traditional NLP techniques with modern Transformer-based language models to identify meaningful financial topics and classify sentiment. Multiple feature extraction methods and machine learning algorithms were evaluated to compare their effectiveness on financial text classification.

---

## ✨ Features

- Financial news text preprocessing
- Text cleaning using NLTK and spaCy
- TF-IDF feature extraction
- Word2Vec embeddings
- Topic Modeling using Latent Dirichlet Allocation (LDA)
- Sentiment Analysis using Machine Learning
- Sentiment Analysis using RoBERTa
- Comparative model evaluation

---

## 🛠 Technologies

- Python
- Pandas
- NumPy
- NLTK
- spaCy
- Gensim
- Scikit-learn
- Hugging Face Transformers
- PyTorch
- Matplotlib

---

## 🤖 Models Implemented

### Topic Modeling

- Latent Dirichlet Allocation (LDA)

### Classical Machine Learning

- Logistic Regression
- Linear Support Vector Machine (SVM)

### Transformer-based Deep Learning

- RoBERTa

---

## 📂 Repository Structure

```text
Financial-NLP-Topic-Modeling-Sentiment-Analysis/
│
├── notebooks/
│   └── Financial_NLP_Project.ipynb
│
├── report/
│   └── Project_Report.pdf
│
├── presentation/
│   └── Project_Presentation.pdf
│
├── data/
│   └── README.md
│
├── images/
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/pravee2063/Financial-NLP-Topic-Modeling-Sentiment-Analysis.git
cd Financial-NLP-Topic-Modeling-Sentiment-Analysis
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## 📊 Dataset

This project uses the **FinancialPhraseBank** dataset for topic modeling and sentiment analysis.

The dataset is **not included** in this repository due to its licensing terms.

### Download

Download the dataset from:

**https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-for-financial-news**

Place the dataset in:

```text
data/all-data.csv
```

The notebook expects the dataset in this location.

### Citation

Malo, P., Sinha, A., Korhonen, P., Wallenius, J., & Takala, P. (2014).

*Good Debt or Bad Debt: Detecting Semantic Orientations in Economic Texts.*

Journal of the Association for Information Science and Technology.

---

## 🚀 Workflow

1. Load the FinancialPhraseBank dataset.
2. Preprocess the text:
   - Cleaning
   - Tokenization
   - Stopword Removal
   - Lemmatization
3. Generate TF-IDF and Word2Vec features.
4. Discover latent topics using LDA.
5. Train classical Machine Learning models:
   - Logistic Regression
   - Support Vector Machine
6. Perform Transformer-based sentiment analysis using RoBERTa.
7. Compare and evaluate model performance.

---

## 📈 Results

This project demonstrates an end-to-end NLP workflow combining traditional machine learning with transformer-based models.

Highlights include:

- Comprehensive NLP preprocessing pipeline
- Topic discovery using Latent Dirichlet Allocation (LDA)
- Feature extraction using TF-IDF and Word2Vec
- Sentiment classification using Logistic Regression and SVM
- Context-aware sentiment prediction using RoBERTa
- Comparative analysis of classical ML and transformer models

---

## 👥 Team

This repository contains the implementation of an academic group project completed as part of the **Data Mining** course at **South Asian University**.

### Team Members

- Awantika Krishna
- Bindiya Anand
- Praveena P

---

## 🤝 My Contributions

My contributions to this project included:

- Designing parts of the NLP preprocessing pipeline
- Text preprocessing and feature engineering
- Implementing and evaluating machine learning models
- Supporting transformer-based sentiment analysis
- Contributing to project documentation and result analysis

---

## 🔮 Future Work

Potential extensions of this project include:

- BERTopic for topic modeling
- Fine-tuning finance-specific transformer models
- Named Entity Recognition (NER)
- Aspect-Based Sentiment Analysis (ABSA)
- Interactive Streamlit dashboard
- Deployment as a web application

---

## 📚 References

1. Malo et al. (2014). FinancialPhraseBank Dataset.
2. Hugging Face Transformers Documentation.
3. Scikit-learn Documentation.
4. Gensim Documentation.
5. NLTK Documentation.
6. spaCy Documentation.

---
