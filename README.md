# Twitter-Sentiment-Analysis

Project Overview:

  This project performs sentiment analysis on tweets collected from Twitter. The dataset contains 1.6 million tweets, each labeled with sentiment:
      0 = Negative
      2 = Neutral
      4 = Positive
  
  The goal is to build and compare various machine learning classification models to accurately predict the sentiment of tweets based on their text content.

Dataset Description

  The dataset was scraped using the Twitter API and includes the following fields:
   1. target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
   2. ids: The id of the tweet .
   3. date: The date of the tweet (Sat May 16 23:58:44 UTC 2009)
   4. flag: The query. If there is no query, then this value is NO_QUERY.
   5. user: The user that tweeted
   6. text: The text of the tweet.

Objective: 

  Using this dataset, we aim to:

    Preprocess raw tweet text

    Extract features (Bag of Words, TF-IDF, etc.)

    Train multiple machine learning classifiers (e.g., Logistic Regression, SVM, Random Forest)

    Evaluate their performance using metrics like accuracy, confusion matrix, and classification report
