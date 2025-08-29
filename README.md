# Spam SMS Detector

## 📋 Overview

This project is an end-to-end machine learning solution for classifying text messages as either "ham" (legitimate) or "spam". It serves as a practical demonstration of a complete Natural Language Processing (NLP) pipeline, from initial data ingestion to model training and evaluation.

The goal is to build a highly accurate and reliable classifier that can filter out unwanted spam messages.

## 📊 Dataset

This project uses the well-known SMS Spam Collection Dataset, which is available on Kaggle. The dataset contains over 5,500 messages labeled as either "ham" or "spam."

Source Link: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

## ✨ Features

- Comprehensive Data Preprocessing: The project includes robust text cleaning and normalization steps to handle raw SMS data.

  - Punctuation and Symbol Removal

  - Lowercase Conversion

  - Stop Word Filtering (e.g., "the", "is", "a")

  - Lemmatization (reducing words to their root form)

- Vectorization Techniques: Converts cleaned text into numerical feature vectors.

  - Bag-of-Words (BoW)

  - TF-IDF (Term Frequency-Inverse Document Frequency)

- Model Training & Comparison: Explores and compares the performance of several classification algorithms.

  - Multinomial Naive Bayes (MNB)

  - Support Vector Machines (SVC)

  - Logistic Regression

  - Performance Evaluation: Utilizes standard machine learning metrics tailored for this task.

- Accuracy, Precision, Recall, and F1-Score

  - Confusion Matrix visualization for a clear understanding of model errors.

- Deployment-Ready Code: The final model is saved using pickle for easy integration into a web application or API.

- Interactive Demo: A Jupyter Notebook provides a step-by-step walkthrough and an interactive cell to test the classifier with new messages.

## 🛠️ Technologies & Libraries

- Python 3.x

- scikit-learn: Machine learning models and utilities.

- NLTK (Natural Language Toolkit): Core library for text processing.

- pandas: Data manipulation and analysis.

- Jupyter Notebook: For an organized and reproducible workflow.

- matplotlib & seaborn: For data visualization.

- pickle: For model persistence.

