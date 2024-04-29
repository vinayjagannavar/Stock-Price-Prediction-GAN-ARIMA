
# Sentimental Analysis of the Stock Market through Twitter.

## Table of Contents
- Introduction
- Installation
- Usage
- Features
- Configuration
- Contributors

## Introduction
Sentiment analysis of the stock market through Twitter involves collecting tweets from 2015 to 2019, preprocessing them, and applying NLP and machine learning techniques to gauge sentiment. This analysis, combined with GAN and ARIMA models for stock prediction and sentiment analysis using VADER and AFINN lexicons, offers a comprehensive approach. By aggregating sentiment scores over time and visualizing trends, investors and analysts gain insights into market sentiment, aiding in decision-making, risk management, and trading strategies. Evaluation of the sentiment analysis model ensures reliability, contributing to informed investment decisions.

## Installation
To set up this project, you will need to install several Python dependencies. Ensure you have Python installed and then run:
```
pip install numpy pandas matplotlib seaborn scikit-learn nltk vaderSentiment yfinance tensorflow
```

## Usage
To use this project, start by uploading your Twitter dataset (Tweet.csv and Company_Tweet.csv). The data should be in a structured format, ideally CSV, containing tweets and their metadata. You can upload the data using the provided upload functionality in the script.

### Datasets
[Tweets dataset](https://www.kaggle.com/datasets/omermetinn/tweets-about-the-top-companies-from-2015-to-2020?select=Tweet.csv)

## Features
The project includes several key features:

**Data Preprocessing:** Cleans and prepares Twitter data for analysis.
Sentiment Analysis: Utilizes both Afinn and Vader to calculate sentiment scores. 

**Stock Price Analysis:** Integrates with Yahoo Finance to correlate stock prices with tweet sentiments.

**Predictive Modeling:** Implements GANs and ARIMA for predicting Google stock prices.

## Dependencies
This project relies on the following Python libraries:

- NumPy
- Pandas
- TensorFlow
- Matplotlib
- Seaborn
- Scikit-Learn
- NLTK
- VaderSentiment
- yfinance

## Configuration
No specific configuration is needed to run this project.