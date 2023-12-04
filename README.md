# SpamDetection

#Introduction
This project focuses on building and evaluating three different pipelines for spam detection. Each pipeline incorporates various preprocessing techniques, feature engineering, and machine learning models.

# Usage
#Google Collab Setup
To use the provided Google Colab notebook, follow these steps:

-Open the notebook in Google Colab.
-Mount your Google Drive by executing the first cell.
-Install required libraries using the provided cell.
-Load and preprocess the dataset as demonstrated in the notebook.

# Model Evaluation
-Pipeline 1: Data Preprocessing + Sparse Embeddings (TF-IDF) + Logistic Regression
-Pipeline 2: Data Preprocessing + Manual Features + XGBoost
-Pipeline 3: Combine Manual Features and TF-IDF Vectors + Logistic Regression

# Features
-Data preprocessing using custom scripts and libraries.
-Utilization of machine learning models such as Logistic Regression and XGBoost.
-Evaluation metrics include F1 score, precision, recall, and accuracy.

# Evaluation
The project evaluates the performance of each pipeline on a test dataset. The chosen pipeline achieves an F1 score of 0.93, indicating effective spam detection capabilities.
