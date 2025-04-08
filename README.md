# 🧠 Sentiment Analysis & Mental Health Signal Detection from Tweets

This project analyzes Twitter data to classify sentiment and explore early indicators of mental health patterns. It uses multiple machine learning models and visualizations to provide insights into user emotion and behavior.

---

## 📂 Dataset

The primary dataset used is [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140), consisting of **1.6 million tweets** labeled as:
- `0` = Negative sentiment
- `4` = Positive sentiment

---

## ✅ Completed Tasks

- ✅ Cleaned and preprocessed tweet data
- ✅ Performed Exploratory Data Analysis (EDA)
- ✅ Applied TF-IDF Vectorization
- ✅ Trained and evaluated:
  - Logistic Regression (77.3% accuracy)
  - Naive Bayes (75.7% accuracy)
  - SVM (77.4% accuracy)
- ✅ Explored Bigrams (Unigrams + Bigrams) to boost model performance
- ✅ Performed cross-validation & feature importance extraction
- ✅ Created user-based sentiment trend visualizations

---

## 📊 Visual Insights

- Tweet length vs sentiment distribution  
- Daily/Hourly sentiment fluctuations  
- Most common words by sentiment class  
- User-based sentiment tendencies

---

## 🚧 Future Work

- Integrate multi-label mental health datasets
- Train deep learning models (e.g., LSTM, DistilBERT)
- Improve sarcasm and mixed-tone detection
- Build a front-end interface for real-time sentiment classification

---

## 📦 Dependencies

- Python 3.8+
- scikit-learn
- pandas, numpy
- seaborn, matplotlib
- `transformers` (for BERT-based experiments)
- Jupyter Notebook

Install required libraries:
```bash
pip install -r requirements.txt
