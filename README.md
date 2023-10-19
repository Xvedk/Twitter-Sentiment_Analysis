# Twitter-Sentiment_Analysis
Sentiment analysis on Twitter involves using natural language processing techniques to determine the emotional tone of tweets, categorizing them as positive, negative, or neutral. This process helps businesses and researchers gauge public opinion, track trends, and make data-driven decisions by analyzing the sentiments expressed in Twitter data.
Download the dataset from-- https://www.kaggle.com/datasets/kazanova/sentiment140


The above code appears to be a Python script for performing sentiment analysis on a dataset of tweets. Here's a summary of the key steps and actions taken in the code:

Importing Libraries: The code starts by importing necessary Python libraries, including pandas, numpy, nltk, and various components from sklearn for natural language processing (NLP) and machine learning.

Loading Data: The code reads a dataset from a CSV file, with specified column names and encoding. It then samples and displays the first few rows of the dataset to get an overview.

Data Preprocessing: Various data preprocessing steps are performed on the tweet text, including converting to lowercase, removing stopwords, punctuations, repeating characters, URLs, and numeric numbers. Tokenization, stemming, and lemmatization are also applied to the text.

Word Clouds: The code generates word clouds to visualize the most frequent words in both positive and negative tweets.

Data Splitting: The dataset is split into training and testing data. Text data is transformed into TF-IDF vectors, which are used as features for the machine learning models.

Model Training and Evaluation: Two machine learning models are trained and evaluated on the sentiment analysis task:

Bernoulli Naive Bayes (BNB): The code trains a BNB model and evaluates its performance using metrics like precision, recall, F1-score, and a confusion matrix. It also calculates the ROC AUC score and plots ROC curves for each class.

Linear Support Vector Classifier (SVC): Similarly, an SVC model is trained and evaluated using the same metrics and ROC curves.

Model Comparison: The code concludes by comparing the performance of both models in terms of accuracy, precision, recall, and F1-score, as well as their ROC AUC scores.

Summary: The code aims to perform sentiment analysis on tweet data using two different machine learning models, preprocess the text data, and evaluate the models' performance. It primarily focuses on binary sentiment classification (positive and negative) and visualizing the results using ROC curves and word clouds.
