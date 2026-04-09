# 🎬 IMDb Sentiment Analysis using NLP & Machine Learning

## 📌 Overview
This project implements a complete Natural Language Processing (NLP) pipeline for sentiment analysis on the IMDb movie reviews dataset.  
The goal is to classify reviews as positive or negative using preprocessing techniques, vectorization methods, and machine learning models.

---

## 🎯 Objectives
- Apply NLP preprocessing techniques:
  - Tokenization
  - Stopword removal
  - Stemming & Lemmatization
- Convert text into numerical form using:
  - CountVectorizer
  - TF-IDF
- Build classification models:
  - Naive Bayes (manual + sklearn)
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Deep Learning (Dense Neural Network)
- Evaluate performance using:
  - Accuracy
  - F1 Score
  - Confusion Matrix

---

## 📂 Dataset
- IMDb Movie Reviews Dataset (50,000 reviews)
- Balanced dataset:
  - 25,000 Positive
  - 25,000 Negative

---

## ⚙️ NLP Pipeline

### 🔹 1. Exploratory Data Analysis (EDA)
- Review length distribution
- Word count analysis
- Class distribution visualization

### 🔹 2. Text Preprocessing

#### ✅ Manual (From Scratch)
- Custom tokenizer
- Manual stopword removal
- Rule-based stemming

#### ✅ Library-Based (NLTK)
- Tokenization using NLTK
- Stopword removal
- Porter Stemmer
- WordNet Lemmatizer

---

### 🔹 3. Advanced NLP Techniques
- POS Tagging (scratch + NLTK)
- Named Entity Recognition (NER)
- N-Grams (bi-grams, tri-grams)
- Word Embeddings (Word2Vec)
- Text Similarity (Cosine Similarity)
- Sentiment Analysis (Rule-based + VADER)

---

## 🔢 Feature Engineering

### 📊 Vectorization Techniques
- CountVectorizer (Bag of Words)
- TF-IDF Vectorizer

---

## 🤖 Models Implemented

### 🔹 Machine Learning Models
- Manual Naive Bayes (from scratch)
- Multinomial Naive Bayes (sklearn)
- Logistic Regression
- Linear Support Vector Machine (SVM)

### 🔹 Deep Learning Model
- Dense Neural Network (TensorFlow/Keras)

---

## 📈 Results & Performance

| Model | Vectorizer | Accuracy | F1 Score |
|------|-----------|----------|----------|
| Naive Bayes | TF-IDF | ~85% | ~84% |
| Logistic Regression | TF-IDF | ~90% | ~89% |
| Linear SVM | TF-IDF | ⭐ ~92% | ⭐ ~90% |
| Deep Learning (Dense NN) | TF-IDF | ~89% | ~88% |

👉 Best Model: Linear SVM with TF-IDF

---

## 📊 Visualizations

Add your generated images in an `images` folder:

![EDA Plot](images/imdb_eda_plot.png)
![Confusion Matrix](images/imdb_confusion_matrices.png)
![Model Comparison](images/imdb_model_comparison.png)

---

## 🧠 Key Insights
- TF-IDF outperforms CountVectorizer for sentiment analysis
- Linear SVM performs best on high-dimensional text data
- Deep learning performs comparably but not significantly better
- Lemmatization improves model understanding over stemming

---

## 🛠️ Tech Stack
- Python
- NLTK
- Scikit-learn
- TensorFlow / Keras
- Gensim
- spaCy
- Matplotlib & Seaborn

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/imdb-sentiment-analysis.git
cd imdb-sentiment-analysis
pip install -r requirements.txt
jupyter notebook
