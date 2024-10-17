## Restaurant Sentiment Analysis and Image Classification
This project performs a comprehensive sentiment analysis on restaurant reviews, leveraging Hugging Face's powerful NLP models. The workflow includes the following steps:

# Sentiment Analysis of Text Reviews: 
We analyze customer reviews using pre-trained sentiment analysis models from Hugging Face to derive sentiment scores (positive, negative, neutral).

# Correlation with Customer Ratings: 
We calculate the correlation between the derived sentiment scores and the corresponding customer ratings to understand how closely the sentiment matches the given ratings.

# Image Classification using Sentiment Labels: 
The sentiment scores from the text reviews are then used as labels to train a deep learning model for classifying images of restaurants. This deep learning model uses the sentiment values (positive, negative, etc.) as labels, allowing for visual sentiment classification.

# Key Components:
# Sentiment Analysis: 
Utilizing Hugging Face Bert transformer for text-based sentiment analysis.
# Correlation Analysis:  
Investigating the relationship between review sentiment and customer ratings.
# Deep Learning Model: 
Training a CNN (Convolutional Neural Network) on restaurant images using the derived sentiment labels.
# Dataset: 
Restaurant review text and customer ratings, along with corresponding restaurant images.
https://www.kaggle.com/datasets/denizbilginn/google-maps-restaurant-reviews/data
