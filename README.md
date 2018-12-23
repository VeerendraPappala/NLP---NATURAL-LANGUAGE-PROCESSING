
# Linguipedia Codefest - Natural Language Processing

## Problem Statement

Sentiment analysis remains one of the key problems that has seen extensive application of natural language processing. This time around, given the tweets from customers about various tech firms who manufacture and sell mobiles, computers, laptops, etc, the task is to identify if the tweets have a negative sentiment towards such companies or products.

##  Understanding the Problem statement

The objective of this task is to detect the negative comments from the customers about various tech firms who manufacture and sell mobiles, computers, laptops, etc So, the task is to classify negative sentiment tweets from other tweets towards other companies.
Formally, given a training sample of tweets and labels, where label ‘1’ denotes the tweet is negative and label ‘0’ denotes the tweet is not negative, the objective is to predict the labels on the given test dataset.

## Evaluation Metric

The metric used for evaluating the performance of classification model would be **weighted F1-Score**.


## FLOW OF THE PROJECT:
  
  ### 1. Understanding the Problem statement
  
  ### 2. TEXT PREPROCESSING AND CLEANING
         * IMPORTING REQUIRED PACKAGES
         * REMOVING TWITTER HANDLE( @USER )
         * Removing Punctutations,Special characters and Numbers
         * Stop Word Removal
         * TOKENIZATION
         * LEMMATIZING
         * Removing Redundant words
   ### 3. Story Generation and Visualization from Tweets
         * Understanding the common words used in the tweets: WordCloud
         * Words in non-negative comments
         * Words in negative comments
        
   ### 4. Extracting Features from Cleaned Tweets     
   
   ### 5. Model Building : Sentiment Analysis 
     Algorithms that can be applied:
        * Logistic Regression
        * RandomForest
        * Support Vector Machine
        * XGBoost
        * Naive Bayes
        * Neural Networks
         
         
