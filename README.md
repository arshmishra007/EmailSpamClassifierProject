# EmailSpamClassifierProject
## Project Overview

This project is an email spam classifier that uses the Naive Bayes algorithm (Multinomial and Bernoulli) to detect spam messages. The model is trained using the SMS Spam Collection dataset and implements text preprocessing, feature extraction using CountVectorizer, and model evaluation using ROC curves.

## Dataset
**Source**: SMS Spam Collection Dataset (https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
# Columns:
**v1**: Label (ham/spam)
**v2**: Message content

## Features Used
**Bag-of-Words Representation**: Using CountVectorizer with stop words removal.

**SMOTE (Synthetic Minority Over-sampling Technique)**: To balance class distribution.

## Model Training Steps

**Load and preprocess the dataset**: Convert labels, clean text.

**Train-test split**: Before applying SMOTE.

**Feature extraction**: Using CountVectorizer (Bag-of-Words approach).

**Apply SMOTE**: To balance dataset before training.

**Train Naive Bayes models**: Using MultinomialNB and BernoulliNB.

**Evaluate models**: Using accuracy, classification reports, and ROC curves.

## Model Evaluation

**Accuracy & Classification Report**: Printed for both models.

**ROC Curve**: Plotted to compare model performance.

## Author

**@arshmishra007**


