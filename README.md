# Tweet Multi-Class Classification
![Python](https://img.shields.io/badge/Python-3.10-blue)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Last Commit](https://img.shields.io/github/last-commit/Christiana123-addo/tweet-classification)
![Repo Size](https://img.shields.io/github/repo-size/Christiana123-addo/tweet-classification)
![Stars](https://img.shields.io/github/stars/Christiana123-addo/tweet-classification?style=social)


This project focuses on the multi-class classification of tweets, assigning each tweet to a specific category using various machine learning models and NLP techniques.

## Objective
To compare different text preprocessing pipelines and machine learning algorithms for effective tweet classification.

## Models Used
- CountVectorizer + Naive Bayes
- TF-IDF + Naive Bayes
- Multi-layer Perceptron (MLP)
- Gradient Boosting Classifier

## Dataset
- The dataset used is sourced from [Kaggle] or a local CSV file.
- Each tweet is labeled into one of several categories:
  - `pop_culture`
  - `sports_&_gaming`
  - `daily_life`
  - `science_&_technology`
  - `business_&_entrepreneurs`
  - `arts_&_culture`

## Requirements
Install all dependencies using:

```bash
pip install -r requirements.txt

## Evaluation Metrics
Performance of the models is compared using the following metrics:

- Accuracy – Overall correctness of the model.
- Precision – How many selected items are relevant.
- Recall– How many relevant items are selected.
- F1-score – Harmonic mean of precision and recall.
- Confusion Matrix – Visual breakdown of predictions vs actual values.

