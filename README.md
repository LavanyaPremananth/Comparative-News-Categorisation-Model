# Comparative-News-Categorisation-Model

Comparative Analysis of Statistical and Embedding-Based Models for News Categorization. This project aims to develop a text classifier for categorizing news articles, specifically targeting fake news detection. The goal is to compare the performance of traditional statistical models and modern embedding-based models, evaluating their efficacy in news categorization.

### Objectives
- Explore and compare the effectiveness of statistical and embedding-based models in news categorization.
- Assess the performance of models such as Naïve Bayes, Logistic Regression, Stochastic Gradient Descent (SGD), and Long Short-Term Memory (LSTM).
- Utilize frequency-based embeddings like CountVectorizer and TF-IDF, and prediction-based embeddings like Word2Vec.

### Feature Engineering
- **Frequency-based Word Embedding:** Traditional approaches like Bag of Words (BoW), term frequency, and TF-IDF are foundational but often neglect semantic relationships between words.
- **Prediction-based Word Embedding:** Word2Vec, introduced by Mikolov et al., and FastText, proposed by Stein et al., construct vector representations of words capturing semantic similarities and morphological information.

### Dataset Description
The dataset used for this research is the "News Aggregator" dataset from the UCI Machine Learning Repository, covering news articles from March 10 to August 10, 2014.

- **Content and Format:** The dataset is in tab-delimited CSV format.
- **Columns:**
  - `ID`: Numeric ID of the news page
  - `TITLE`: Title of the news article
  - `URL`: URL of the news page
  - `PUBLISHER`: Name of the publisher
  - `CATEGORY`: News category (b for business, t for science and technology, e for entertainment, m for health)
  - `STORY`: Alphanumeric ID of the cluster containing news about the same story
  - `HOSTNAME`: Hostname of the URL
  - `TIMESTAMP`: Approximate publication time of the news article in milliseconds since January 1, 1970, GMT

Link to Dataset: [News Aggregator Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/news-aggregator-dataset)

Source and Citation: Gasparetti, F. (2016). News Aggregator. UCI Machine Learning Repository. Retrieved from https://doi.org/10.24432/C5F61C.

## Installation
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd <repository-directory>
