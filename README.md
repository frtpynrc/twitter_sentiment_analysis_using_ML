# Sentiment Analysis with Machine Learning
# Summary
Social media has become a prominent platform for expressing opinions, but it also introduces challenges such as the spread of negativity and hate speech. In this project, we leverage machine learning to analyze sentiments in tweets, categorizing them as either positive or negative.

# Dataset Description
The dataset consists of tweets, with one set labeled for training and another unlabeled set for testing. The objective is to predict sentiments based on the labeled training data.

# Data Pre-Processing
Removing Twitter Handles (@user): Eliminate user mentions to focus on tweet content.
Removing Punctuation, Numbers, and Special Characters: Clean the text for better analysis.
Removing Short Words: Exclude words with a short length.
Tokenization: Split the text into individual words.
Stemming: Reduce words to their base or root form.
# Data Visualization
WordCloud: Visual representation of frequent words.
Bar Plots: Graphical representation of word frequency.
# Feature Extraction
Bag-of-Words Features
The Bag-of-Words model creates a vocabulary of unique words in the training set and represents each document as a matrix where rows correspond to documents and columns to unique words. This matrix captures the frequency of words in each document.

# TF-IDF Features
TF-IDF (Term Frequency-Inverse Document Frequency) is a weight used to evaluate the importance of a word in a document relative to a collection. It combines term frequency and inverse document frequency to calculate a weight for each word.

# Machine Learning Analysis
Logistic Regression:

Trained using Bag-of-Words and TF-IDF features.
F1 Score used for evaluation.
XGBoost:

Employed as a boosting algorithm.
Evaluation based on F1 Score.
Decision Trees:

Applied for classification.
F1 Score used for assessment.
# Model Comparison
Comparison of F1 Scores reveals that Logistic Regression with TF-IDF features performs best.
