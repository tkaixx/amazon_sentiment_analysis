# Amazon_Sentiment_Analysis

## Overview
Sentiment Analysis using VADER and Roberta Models to derive polarity scores for Amazon Fine Food Customer Reviews.
Data visualization in Word Cloud for cleaned text reviews to understand the most frequently-used words found for positive, neutral, and negative sentiment respectively.

## Data
Data source is from Kaggle Dataset, Amazon Fine Food Reviews
https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews 

## Sentiment Analysis Techniques
1. VADER (Valence Aware Dictionary and sEntiment Reasoner) uses Bag of words approach
  - derive positive, neutral, negative polarity scores & compound score from text
2. Pre-trained Roberta Model from Hugging Face (https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment-latest) 

## Word Cloud Analysis
Steps Taken:
1. Clean text by converting all words to lowercases, removing stopwords, numbers & punctuations
2. Perform tokentization
3. Generate separate word clouds for clean text grouped by sentiment labels (positive, neutral & negative)

![image](https://github.com/user-attachments/assets/124e1910-1840-43f5-ad0f-b8823cb57591)

![image](https://github.com/user-attachments/assets/24523676-0b69-4950-aed5-99ff9b4bd514)

![image](https://github.com/user-attachments/assets/0af197ae-4f8e-4631-b77f-11ba497df9fa)



