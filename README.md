# Predicting sentiment associated to Tweets
Aditya Radjou

## Abstract
According to Statista, there are more than 200 million users of Twitter: this huge platform is a place where many ideas flow. On Twitter, people express their opinions. Analyzing their sentiments is more than useful. For example, it can assess the popularity of politicians and be the basis of opinion polls. It can be used to detect messages that convey negative information (like racism, bullying…).Sentiment analysis is a powerful tool, and this paper aims at implementing
this Artificial Intelligence in Twitter.

This project aims at predicting the sentiment associated to tweets (positive, negative, or neutral). To do so, I have tried 4 methods:
- TextBlob: This is a pre-trained model that can be directly used to extract sentiment from tweets.
- VADER: This is also a pre-trained model but specifically designed for sentiment analysis of social media texts.
- Naive Bayes Classifier (NBC): I trained this model on 20000+ tweets.
- BERT: I finetuned this pre-trained model with 20000+ tweets.

I used the F-1 Score to assess and compare the performance of these models.

## Table of results:

### F-1 Score of the 4 models

| Model        | F-1 Score |
|--------------|:---------:|
| TextBlob     | 0.59      |
| VADER        | 0.48      |
| NBC          | 0.65     |
| BERT         | 0.83     |




