This repository contains the code implementation and analysis for my research project "Relationship between Tweets Sentiment and Stock Price" completed at Erasmus University for the Learning from Big Data module.

## **Project Overview**

This project investigates whether public sentiment captured from social media (Twitter) can predict stock price fluctuations. Using Nvidia Corporation as a case study, I built from scratch a Naive Bayesian Classifier to analyze tweet sentiment and tested its relationship with subsequent stock price movements.

## **Data Sources**

- **UGC Dataset**: Tweets about Nvidia (Nov 2022 - Feb 2023)
- **Sentiment140 Corpus**: Dataset of labeled tweets used for the lexicon creation
- **Financial Data**: Nvidia stock price from Yahoo Finance

## **Methodology**

- **Data Processing & Filtering**: Removing advertisements, selecting market-closure tweets, and creating a balanced 300-tweet dataset.

- **Lexicon Creation**: Preprocessing corpus text (lowercase, tokenization), balancing positive/negative tweets, and generating word-sentiment associations.

- **Naive Bayesian Classification**: Implementing additive smoothing, calculating word-sentiment likelihoods, and computing posterior probabilities.

- **Market Correlation Analysis**:
   - **Market Condition Definition**: Establishing ±2% price change threshold
   - **Linear Regression**: Testing relationship between tweet sentiment and stock price fluctuations

- **Performance Evaluation**
