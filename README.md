# Sentiment Analysis

## Overview
This project explores sentiment classification using basic machine learning techniques on Portuguese tweets.
The goal is to build a simple baseline and understand how different models perform on text data.

## Objective
Classify tweets into sentiment categories.

## Stack
- Python
- pandas
- scikit-learn
- Jupyter Notebook

## Workflow
- Load dataset
- Basic data inspection
- Split data into training and testing sets (multiple splits)
- Convert text into numerical features (CountVectorizer)
- Train different models
- Compare results using accuracy and confusion matrix

## Models Used
- Multinomial Naive Bayes
- Decision Tree
- Linear SVC

## Results
The models achieve reasonable performance for a simple baseline.

Linear SVC showed the best results among the tested models.

## Notes
- Dataset contains Portuguese tweets
- No hyperparameter tuning was applied
- Focus is on understanding the workflow rather than optimizing performance

## Reference
Initial study adapted from a public example and reorganized into a cleaner project structure.
