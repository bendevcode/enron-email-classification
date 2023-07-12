# enron-email-classification
Enron Email Classification

## Introduction
This repository contains the code and analysis for the Enron email classification project. The project's goal is to create a supervised classification pipeline to classify emails as spam or non-spam.

## Author
- Name: Oluyori Oluwagbemiga Benjamin


## Project Overview
The Enron email dataset is a collection of emails from the Enron corporation, manually classified as spam and non-spam. This project aims to develop a classification model that can accurately classify emails as spam or non-spam.

## Project Structure
The project is structured as follows:
- `data/`: This directory contains the Enron email dataset in txt format.
- `code/`: This directory contains the Python code for data preparation, exploratory data analysis, feature extraction, and model training and evaluation.
- `results/`: This directory contains the results and visualizations generated during the analysis.
- `README.md`: This file provides an overview of the project and instructions for reproducing the experiments.

## Data Preparation
The Enron email dataset consists of 1,500 spam and 3,672 ham emails in txt format. The data preparation step involves reading and preprocessing the text files, creating a data frame, removing unnecessary prefixes, handling duplicates, and splitting the dataset into training and test sets.

## Exploratory Data Analysis
The exploratory data analysis explores the dataset's characteristics, such as the distribution of spam and ham emails, the most frequent words, and email lengths. Visualizations such as bar charts, word clouds, and box plots are used to gain insights into the dataset.

## Feature Extraction
In this project, a bag-of-words model is used to transform the text data into a fixed-length representation suitable for machine learning models. The CountVectorizer and TfidfVectorizer methods from scikit-learn are utilized for feature extraction.

## Supervised Classification
Several supervised classification models, including Logistic Regression, Naive Bayes, Random Forest, and Support Vector Machines, are trained and evaluated using the Enron email dataset. The models are assessed based on accuracy, precision, recall, F1-score, and other performance metrics.

## Model Selection
The best-performing model is selected based on its performance on the test set. Hyperparameter tuning is performed using cross-validation, and the model with the highest accuracy is chosen as the final model.

## Model Evaluation
The selected model is evaluated on the test set to assess its generalization ability. Performance metrics, such as accuracy, precision, recall, F1-score, and the ROC curve, are analyzed to measure the model's effectiveness in classifying emails.

## Conclusion
The Enron email classification project demonstrates the successful development of a supervised classification pipeline to classify emails as spam or non-spam. The selected model achieves high accuracy and performance on the test set, indicating its potential for real-world application.


