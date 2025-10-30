# 🛫 US Airlines Sentiment Analysis

This project explores public sentiment toward major US airlines using real-world Twitter data. The goal is to understand how passengers feel about different airlines and what factors drive positive or negative perceptions.

## 📊 Project Overview

Air travel experiences often evoke strong emotions, both positive and negative. By analyzing tweets about major US airlines, this project aims to uncover key patterns in customer sentiment and highlight areas of satisfaction or concern.

## ⚙️ Key Steps

- Data Cleaning & Preparation

- Removed missing and duplicate entries

- Cleaned tweet text (punctuation, links, mentions, stopwords)

- Standardized airline names and categories

- Exploratory Data Analysis (EDA)

- Distribution of tweets by sentiment and airline

- Frequency of tweet sources (Android, iPhone, web, etc.)

- Word frequency analysis to identify common themes

- Sentiment Classification

- Classified tweets as Positive, Negative, or Neutral using VADER (Valence Aware Dictionary and sEntiment Reasoner)

- Compared sentiment trends across different airlines

## Visualization

- Bar charts and pie charts showing sentiment distribution

- Word clouds highlighting common words in each sentiment category

- Comparative plots to assess airline performance perception

## 💡 Key Insights

Negative sentiments dominate across most airlines, especially regarding delays and poor service.

Positive tweets often highlight friendly staff, comfort, and smooth experiences.

Certain airlines have more balanced sentiment distributions, indicating stronger customer engagement strategies.

## 🧰 Tools & Libraries

- Python

- Pandas, NumPy

- Matplotlib, Seaborn

- VADER Sentiment Analyzer / TextBlob

- Jupyter Notebook


## 📈 Future Improvements

- Implement a deep learning-based sentiment model (e.g., LSTM or BERT)

- Include real-time tweet streaming and dashboard visualization

- Perform topic modeling to identify main discussion themes
