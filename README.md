# 📰 Fake News Detection

This project aims to classify news articles as **real** or **fake** using Natural Language Processing (NLP) techniques and machine learning algorithms.

---

## 📁 Dataset

- **Source**: [Kaggle – Fake News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
- **Features**:
  - `title`: Headline of the news
  - `text`: Full news content
  - 'author name': writer of the article
  - `label`: `1` for **fake**, `0` for **real**

---

## 🎯 Objective

To build a **binary classification model** that can identify whether a news article is real or fake based on its textual content.

---

## 🧹 Data Preprocessing

- Handled null values
- Merged title and text columns for better context
- Removed:
  - Punctuation
  - Stopwords
  - Special characters
- Converted text to lowercase
- Tokenized and stemmed words

---

## 🔠 Text Vectorization

- Used **TF-IDF Vectorizer** to convert text into numerical features
  - Captures importance of a word based on frequency across documents

---

## 🤖 Models Tried

- **Logistic Regression**
  ----

## 📊 Evaluation Metrics

- **Accuracy**


