# 📰 News Article Sentiment Analysis

A simple NLP project that predicts the sentiment of a news article as **Positive**, **Negative**, or **Neutral** using **TF-IDF** and **Logistic Regression**.

---

## 📌 Features

- Analyze the sentiment of news articles
- Predicts:
 - 😊 Positive
  - 😐 Neutral
  - ☹️ Negative
- Minimum 100-word validation before analysis
- Simple and beginner-friendly Flask web interface
- Fast prediction using a trained machine learning model

---

## 🛠️ Technologies Used

- Python
- Flask
- Pandas
- Scikit-learn
- Joblib
- HTML
- CSS
- JavaScript

---

## 🧠 NLP Techniques Used

- Text Cleaning
- Tokenization (via TF-IDF)
- Stop Word Removal
- TF-IDF Vectorization

---

## 🤖 Machine Learning Model

- Logistic Regression

---

## 📂 Project Structure

```
Sentiment-Analysis/
│
├── app.py
├── train.py
├── news.csv
├── sentiment_model.pkl
├── tfidf_vectorizer.pkl
├── requirements.txt
├── README.md
│
└── templates/
      └── index.html
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone <repository-url>
cd Sentiment-Analysis
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## 📊 Train the Model

Run:

```bash
python train.py
```

This will generate:

- sentiment_model.pkl
- tfidf_vectorizer.pkl

---

## ▶️ Run the Application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## 🚀 How to Use

1. Open the application.
2. Paste a news article containing at least **100 words**.
3. Click **Analyze**.
4. View the predicted sentiment.

---

## 📈 Workflow

```
News Article
      │
      ▼
Text Cleaning
      │
      ▼
Tokenization
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Logistic Regression
      │
      ▼
Sentiment Prediction
```

---

## 📋 Sample Dataset

| Text | Label |
|------|-------|
| The company reported record profits this year. | Positive |
| Heavy rainfall caused severe flooding in the city. | Negative |
| The meeting was held on Tuesday afternoon. | Neutral |

---

## 📌 Future Improvements

- Better UI Design
- Confidence Score
- Sentiment Visualization
- Upload PDF or TXT files
- Larger Dataset
- Deploy on Render or Railway

---

## 👨‍💻 Author

Developed by Satyajeet as a beginner-friendly NLP project using Flask and Scikit-learn.

---#
