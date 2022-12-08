# TwitterSentimentAnalysis-NLP

## Problem Statement
Build a sentiment analysis based Twitter tweets classifier for the models: Multinomial Naive Bayes, Support Vector Classifier (SVC), SVC with SGD optimizer, Adaboost Classifier having the features: Stopwords filtering, Sentiment analysis, Profanity Detection, TF-IDF Bag of Words representation to classify tweets into two classes: OFF (representing offensive sentiment) and NOT (representing non offensive sentiment).

## Introduction
With growing intolerance, literacy , right to express and comment - whether necessary or otherwise - has created a new wave of war of words. 
Abusive language on online platforms has become a major concern in the past few years. Project objectives:

● Build an offensive language identification classifier.

● Explore the challenges in doing so.

Performed error analysis on the classifier models build to reason the accuracy and misclassifications.

## Data
Data set of tweets annotated for offensiveness. This data was taken from the 2019 SemEval task on offensive language detection. The labels indicating offensive/non-offensive are as follows:

● (NOT) Not Offensive - This post does not contain offense or profanity.

● (OFF) Offensive - This post contains offensive language or a targeted (veiled or direct) offense

For tweets marked as OFF, the third column (category) specifies the type of offensive speech:

● (TIN) Targeted Insult and Threats - A post containing an insult or threat to an individual, a group, or 

● (UNT) Untargeted - A post containing non-targeted profanity and swearing. For tweets marked as NOT, the third column is nan

## Summary:
* Preprocessing:
  1. Stopwords filtering
  2. Sentiment analysis
  3. Profanity Detection
  4. TF-IDF Bag of Words representation
* Models used:
  1. Multinomial Naive Bayes
  2. Support Vector Classifier (SVC)
  3. SVC with SGD optimizer
  4. Adaboost Classifier
