# Sentiment Analysis

## Overview
This project explores sentiment classification using basic machine learning techniques on Portuguese tweets.
The goal is to build a simple baseline and understand how different models perform on text data.

## Objective
Classify tweets into sentiment categories.

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
- Best model: Linear SVC  
- Best accuracy: ~0.78 (30% test split)

## Model Comparison (30% split)
- Naive Bayes: ~0.70  
- Decision Tree: ~0.65  
- Linear SVC: ~0.78  

## Notes
- Dataset contains Portuguese tweets
- Focus is on understanding the workflow rather than optimizing performance

## Reference
Initial study adapted from a public example and reorganized into a cleaner project structure.
