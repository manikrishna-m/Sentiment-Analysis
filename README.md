# Amazon Reviews Sentiment Analysis

## Overview

This project focuses on sentiment analysis of Amazon product reviews using Natural Language Processing (NLP) techniques and machine learning. The goal is to build a model that can predict whether a given review has a positive or negative sentiment.

## Project Structure

### 1. Importing Required Packages
   - Utilizes popular Python libraries such as Pandas, NumPy, Seaborn, Matplotlib, and NLTK for data analysis and natural language processing tasks.

### 2. Reading the DataFrame
   - Loads the Amazon reviews dataset from a CSV file and performs initial exploratory data analysis.

### 3. Text Preprocessing
   - Defines a function `preprocess_reviews` to clean and preprocess the text data. Steps include lowercasing, removing special characters and digits, eliminating stop words, and lemmatization.

### 4. Sentiment Analyzer
   - Utilizes the NLTK Sentiment Intensity Analyzer to assign a polarity score to each review, classifying it as positive (1) or negative (0).

### 5. Selecting Relevant Features
   - Extracts relevant features for model training, including the polarity score and preprocessed review text.

### 6. Train-Test Split
   - Splits the dataset into training and testing sets for model evaluation.

### 7. Word to Vectors
   - Implements functions for converting text data to vectors using Bag of Words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF) techniques. Includes options for n-gram and character-level analysis.

### 8. Model Training
   - Trains a logistic regression model using different vectorization techniques and evaluates model performance using accuracy metrics.
