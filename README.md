# Capstone-Project

# Machine Learning Model Comparison

## Description

This project focuses on evaluating and comparing various machine learning models to analyze a specific dataset. The goal is to identify the most effective model based on performance metrics like accuracy, precision, recall, F1-score, ROC-AUC, False Positive Rate (FPR), and False Negative Rate (FNR). The project is implemented in Python, using Google Colab as the development environment.

## Features

- **Data Preprocessing**: Includes handling missing values, encoding categorical variables, and feature scaling.
- **Exploratory Data Analysis (EDA)**: Provides statistical summaries and visualizations of the dataset.
- **Model Implementation**: Evaluates different machine learning models such as Logistic Regression, K Nearest Neighbors, and Decision Trees.
- **Performance Evaluation**: Each model is assessed using various metrics.
- **Visualization**: Includes detailed visualizations of model performances and error rates.

## How to Use

### Getting Started

1. **Open Google Colab**: Visit [Google Colab](https://colab.research.google.com/) and sign in with your Google account.

2. **Upload the Notebook**: Click on `File` > `Upload notebook` and select the Jupyter notebook file (`.ipynb`) from your computer.

3. **Mount Google Drive** (if your data is stored on Google Drive):
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
