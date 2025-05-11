# CSA
Customer Sentiment Analysis - An NLP-based model to classify customer reviews &amp; extract insights from feedback data

This project performs sentiment analysis on customer product reviews using Natural Language Processing (NLP) techniques from the NLTK library and sentiment scoring from VADER. The dataset used contains Amazon product reviews with labeled sentiment.

---

## 📊 Dataset

- Source: [Amazon Reviews Dataset](https://raw.githubusercontent.com/pycaret/pycaret/master/datasets/amazon.csv)
- Features:
  - `reviewText`: Raw review text by customers
  - `Positive`: Ground truth sentiment (1 for positive, 0 for not positive)

---

## 🧠 Workflow Overview

1. **Text Preprocessing**
   - Tokenization
   - Lowercasing
   - Stop word removal
   - Lemmatization

2. **Sentiment Analysis**
   - Use of VADER sentiment analyzer (`SentimentIntensityAnalyzer`) to classify reviews as positive or not

3. **Evaluation**
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)

---

## 📦 Dependencies

- Python 3.10+
- pandas
- nltk
- scikit-learn (for evaluation metrics)

Install them with:

```bash
pip install pandas nltk scikit-learn
