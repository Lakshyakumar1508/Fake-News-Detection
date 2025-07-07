# Fake-News-Detectiona# 📰 Fake News Detection using NLP & Machine Learning

This project is an AI-powered classifier that detects whether a news article is **real** or **fake**. It uses **Natural Language Processing (NLP)** techniques and a **Passive Aggressive Classifier** trained on both real (manually created) and fake news datasets.

---

## 🎯 Problem Statement

Fake news spreads misinformation and influences public perception. This project aims to help combat this problem by building an intelligent system that classifies news as real or fake.

---

## 📁 Dataset

The dataset is a combination of:

- ✅ **Fake News**: Loaded from `Fake.csv` (Kaggle source)
- ✅ **Real News**: Manually created sample articles with accurate headlines and content

| Column     | Description                           |
|------------|---------------------------------------|
| `title`    | News article title                    |
| `text`     | Full body of the news article         |
| `label`    | Target column: `FAKE` or `REAL`       |

---

## 🧠 Technologies Used

- Python
- pandas, NumPy
- NLTK (text cleaning and stopwords)
- scikit-learn (TF-IDF, ML models, evaluation)
- Matplotlib & Seaborn (visualization)

---

## ⚙️ Workflow

1. **Data Loading** (`Fake.csv` + manually written real articles)
2. **Text Cleaning** (lowercasing, stopword removal, punctuation removal)
3. **Feature Extraction** using **TF-IDF Vectorizer**
4. **Model Training** using:
   - ✅ Passive Aggressive Classifier
   - (You can also try SVM, Logistic Regression, etc.)
5. **Evaluation**:
   - Accuracy
   - Classification report
   - Confusion matrix
6. **Custom Prediction**:
   - You can enter your own news text and get a prediction

---

## 📈 Model Performance

| Metric     | FAKE | REAL |
|------------|------|------|
| Precision  | 0.99 | 0.93 |
| Recall     | 0.99 | 0.92 |
| F1-Score   | 0.99 | 0.92 |
| **Accuracy** | **98.75%** overall |

🔍 Even with limited real data, the model performs well thanks to TF-IDF and Passive Aggressive's effectiveness on text data.

---

## DATASET NOT UPLOADED DUE TO LARGE FILE
