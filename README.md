# Fake-News-
#  Detecting Misinformation in Gold Price News: A Machine Learning Approach 🇮🇳

This repository contains the full implementation of a machine learning pipeline to detect fake news articles related to gold price and investments in the Indian financial media landscape.

##  Project Overview

Gold plays a vital economic and cultural role in India, making it highly vulnerable to misinformation, especially across digital platforms. This project uses NLP and machine learning to:
- Classify gold-related news as **True** or **Fake**
- Identify patterns in fake news using **EDA** and **n-gram analysis**
- Evaluate the performance of multiple ML models for deployment

##  Tools and Libraries Used

- **Python 3.10**
- **Pandas**, **NumPy** – Data manipulation
- **NLTK**, **spaCy** – Natural Language Processing
- **TfidfVectorizer**, **CountVectorizer** – Text vectorization
- **Scikit-learn** – Model training & evaluation
- **Matplotlib**, **Seaborn**, **WordCloud** – Visualization
- **BeautifulSoup**, **requests** – Web scraping


 Features
Text preprocessing: cleaning, tokenization, lemmatization

Word count and word cloud visualization

Time-series analysis of fake news spikes

N-gram analysis of frequent misleading phrases

Model comparison: Logistic Regression, Random Forest, Gradient Boosting, Naïve Bayes, Decision Tree

ROC Curve plotting and 5-fold cross-validation

Manual testing with user input

Test evaluation on unseen news data

**Best Performing Models
**
**Model	Accuracy (Test Data)
Random Forest	98.88%
Naïve Bayes	99.2%
Logistic Regression	98.7%**

Future Work
Include regional (non-English) news for broader coverage

Add deep learning models (LSTM, BERT)

Integrate real-time news feed monitoring

Deploy model as a web app or API
