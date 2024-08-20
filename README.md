# DisasterTweets

## Overview
This project focuses on classifying tweets as either related to disasters or not. The classification is achieved using Natural Language Processing (NLP) techniques, with a Logistic Regression model as the baseline. The project was developed as part of a Kaggle competition, serving as an introduction to NLP and text classification tasks.

## Data
The dataset used in this project is provided by Kaggle and consists of tweets labeled as either disaster-related or not. The dataset is divided into:

Train Data: Contains labeled tweets (1 for disaster, 0 for non-disaster).
Test Data: Contains tweets without labels; the task is to predict these labels.
Sample Submission: A template for the format required by Kaggle for submissions.
Exploratory Data Analysis
Before building the model, an Exploratory Data Analysis (EDA) was conducted to understand the distribution of data, handle missing values, and preprocess the text data. Key steps included:

Visualizing the distribution of the target variable.
Analyzing and imputing missing values in the keyword and location columns.
Cleaning the text data by removing URLs, stopwords, and special characters.

## Modeling
The project uses a Logistic Regression model as the baseline for text classification. The model was trained using TF-IDF (Term Frequency-Inverse Document Frequency) features extracted from the tweet text. Hyperparameter tuning was performed to optimize the model's performance.

## Model Performance
The model achieved an accuracy of approximately 80.7% on the validation set. The performance was better for non-disaster tweets, with opportunities to improve disaster-related tweet classification through advanced models or additional features.
