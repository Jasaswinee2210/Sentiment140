# Sentiment140
# 🧠 Sentiment Analysis on Tweets using Logistic Regression

Welcome to this project on **Tweet Sentiment Classification** using the **Sentiment140** dataset. This repository demonstrates a simple yet powerful approach to determine the sentiment (positive or negative) of tweets using machine learning techniques.

## 📌 Project Overview

This project is part of the Artificial Intelligence and Data Science curriculum at **C.V. Raman Global University** and is developed with guidance from **Cranes Varsity**. It showcases the end-to-end pipeline for text preprocessing, feature extraction, model training, evaluation, and insights using **Logistic Regression**.

---

## 📂 Dataset

- **Source**: [[Sentiment140](http://help.sentiment140.com/for-students)](https://www.kaggle.com/datasets/kazanova/sentiment140/data)
- **Labels**:
  - `0` = Negative
  - `4` = Positive
- **Features**: Tweet text

---

## ⚙️ Technologies Used

- Python 🐍
- pandas, numpy
- NLTK (Natural Language Toolkit)
- scikit-learn (for TF-IDF and Logistic Regression)
- matplotlib / seaborn (for data visualization)

---

## 🚀 Workflow

1. **Data Loading & Inspection**
2. **Text Preprocessing**
   - Cleaning (removing links, mentions, punctuations)
   - Lowercasing
   - Tokenization
   - Stopword Removal
   - Lemmatization
3. **Vectorization** using `TfidfVectorizer`
4. **Model Training** using **Logistic Regression**
5. **Model Evaluation** using accuracy, precision, recall, F1-score
6. **Result Visualization**

---

## 📊 Results

- Achieved an accuracy of approximately 79%
- Logistic Regression provided a good balance between performance and interpretability.

---
