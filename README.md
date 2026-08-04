# 🏨 Hotel Review Sentiment Analysis using NLP & Machine Learning

> A Machine Learning project that classifies hotel reviews as **Positive 😊** or **Negative 😞** using Natural Language Processing (NLP), TF-IDF Vectorization, and Logistic Regression.

---

## 📌 Overview

Customer reviews are one of the most valuable sources of feedback in the hospitality industry. This project analyzes hotel reviews and predicts whether a review expresses a **positive** or **negative** sentiment.

The model is trained on thousands of hotel reviews after extensive text preprocessing and feature extraction, enabling it to accurately classify new user-entered reviews.

---

## 🚀 Features

- ✅ Data preprocessing and cleaning
- ✅ Text normalization using NLP techniques
- ✅ Stopword removal
- ✅ Lemmatization
- ✅ TF-IDF Feature Extraction
- ✅ Logistic Regression Classifier
- ✅ Performance Evaluation
- ✅ Interactive prediction on custom reviews
- ✅ Confusion Matrix and Classification Report
- ✅ Accuracy of approximately **88%**

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Regular Expressions (Regex)
- Jupyter Notebook

---

## 📂 Dataset

The project uses the **Hotel Reviews Dataset**, which contains:

- Positive Reviews
- Negative Reviews
- Reviewer Scores
- Hotel Information

The sentiment label is generated from the reviewer score:

- Reviewer Score ≥ 7 → Positive
- Reviewer Score < 7 → Negative

---

## ⚙️ Project Workflow

```
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Text Preprocessing
   ├── Lowercasing
   ├── Remove Special Characters
   ├── Stopword Removal
   └── Lemmatization
   │
   ▼
TF-IDF Vectorization
   │
   ▼
Train-Test Split
   │
   ▼
Logistic Regression
   │
   ▼
Model Evaluation
   │
   ▼
Custom Review Prediction
```

---

## 🧹 NLP Preprocessing Steps

The reviews undergo several preprocessing operations:

- Convert text to lowercase
- Remove punctuation and numbers
- Tokenization
- Remove English stopwords
- Lemmatization using WordNet
- Join processed words back into clean text

---

## 🤖 Machine Learning Model

The project uses:

- **Algorithm:** Logistic Regression
- **Feature Extraction:** TF-IDF Vectorizer
- **Train-Test Split:** 80:20

---

## 📊 Model Performance

**Accuracy**

```
88%
```

The model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 💻 Sample Prediction

```
Enter a review:
"The rooms were spacious and the staff was very friendly."

Prediction:
Positive Review 😊
```

```
Enter a review:
"The rooms were dirty and the bathroom smelled terrible."

Prediction:
Negative Review 😞
```

---

## 📁 Project Structure

```
Hotel-Review-Sentiment-Analysis/
│
├── Hotel_Reviews.csv
├── Sentiment_Analysis.ipynb
├── README.md
└── requirements.txt
 

## 📈 Future Improvements

- Deep Learning using LSTM
- BERT-based sentiment classification
- Streamlit Web Application
- Flask API deployment
- Multi-class sentiment analysis
- Aspect-based sentiment analysis
- Real-time review prediction


## 🎯 Learning Outcomes

This project demonstrates:

- Natural Language Processing
- Text Cleaning
- Feature Engineering
- TF-IDF Vectorization
- Logistic Regression
- Sentiment Analysis
- Machine Learning Model Evaluation

