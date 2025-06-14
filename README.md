
# Sentiment Analysis of Tweets (TF-IDF + Naive Bayes)

This project classifies tweets into **Positive**, **Neutral**, or **Negative** sentiments using **Natural Language Processing (NLP)** techniques.

##  Tools & Libraries
- Python, Pandas, NumPy
- Scikit-learn (TF-IDF, Naive Bayes, metrics)
- Matplotlib, Seaborn

##  Steps
1. Data cleaning (remove punctuation, URLs, stopwords)
2. TF-IDF vectorization
3. Train-Test split (80-20)
4. Naive Bayes classification
5. Evaluation (accuracy, F1-score, confusion matrix)

## Result
- Accuracy: ~94%
- Best Model: Multinomial Naive Bayes (`alpha=0.1`)

##  Files
- `sentiment_tweets3.csv` – Dataset
- `sentiment_analysis_tfidf_nb.ipynb` – Notebook

##  Run
```bash
pip install -r requirements.txt
jupyter notebook sentiment_analysis_tfidf_nb.ipynb
