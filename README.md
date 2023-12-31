# Twitter Sentiment Analysis with XGBoost

This repository contains a Jupyter notebook that demonstrates the use of Natural Language Processing (NLP) techniques to prepare and analyze a dataset of tweets from [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140). Using the `TF-IDF` vectorizer and the `XGBoost` classifier, the model is trained to predict whether a given tweet has a positive or negative sentiment. Additionally, tweets referencing Amazon are extracted and analyzed in depth.

## Contents

1. Data Preparation
2. Model Training with XGBoost
3. Analysis of Tweets Mentioning Amazon
4. Visualizations

## Visualizations

### Word Clouds
- #### Positive Tweets
![Positive Tweets Word
Cloud](https://github.com/marko-londo/Twitter-Sentiment/blob/main/Images/poscloud.png?raw=true)
- #### Negative Tweets
![Negative Tweets Word Cloud](https://github.com/marko-londo/Twitter-Sentiment/blob/main/Images/negcloud.png?raw=true)

### Word Frequency

![Word Frequency Bar Chart](https://github.com/marko-londo/Twitter-Sentiment/blob/main/Images/wordfreq.png?raw=true)

### Sentiment Analysis for Amazon Tweets

![Amazon Tweets Sentiment Bar Chart](https://github.com/marko-londo/Twitter-Sentiment/blob/main/Images/negpos.png?raw=true)

## How to Use

1. Download the dataset from [Kaggle - Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140).
2. Clone this repository.
3. Ensure you have the necessary libraries installed (`xgboost`, `sklearn`, `matplotlib`, etc.).
4. Open the `.ipynb` file in Jupyter Notebook and run it.

## Insights

After training, the model was used to extract tweets mentioning Amazon, leading
to various insights. Word cloud visualizations and a bar chart for word
frequencies showcase the most common words in positive and negative tweets. The
sentiment analysis bar chart then breaks down the overall sentiment of these
Amazon-related tweets. The model successfully achieved a 72% accuracy rate when predicting tweet sentiments.

