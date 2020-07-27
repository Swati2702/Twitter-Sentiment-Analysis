# Twitter-Sentiment-Analysis
- Kaggle competition: https://www.kaggle.com/arkhoshghalb/twitter-sentiment-analysis-hatred-speech
- Kaggle Project - https://www.kaggle.com/swatisk2702/twitter-sentiment-analysis

The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, our objective is to predict the labels on the test dataset.


Approach:
 1. Preprocessed tweets - lemmantization, tokenization, stemming.
 2. Story Generation and Visualization from Tweets using "Word Cloud".
 3. Used two different encoding schemes to see better performance:
  a. Count Vectorizer (Bag-of-Words)
  b. TF-IDF Vectorizer
 4. Used Logistic Regression Model
 
