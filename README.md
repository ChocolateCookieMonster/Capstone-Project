# Capstone-Project

Description
This project focuses on evaluating and comparing various machine learning models to analyze a specific dataset. The goal is to identify the most effective model based on performance metrics like accuracy, precision, recall, F1-score, ROC-AUC, False Positive Rate (FPR), and False Negative Rate (FNR). The project is implemented in Python, using Google Colab as the development environment.

Features
Data Preprocessing: Includes handling missing values, encoding categorical variables, and feature scaling.
Exploratory Data Analysis (EDA): Provides statistical summaries and visualizations of the dataset.
Model Implementation: Evaluates different machine learning models such as Logistic Regression, K Nearest Neighbors, and Decision Trees.
Performance Evaluation: Each model is assessed using various metrics.
Visualization: Includes detailed visualizations of model performances and error rates.
How to Use
Getting Started
Open Google Colab: Visit Google Colab and sign in with your Google account.

Upload the Notebook: Click on File > Upload notebook and select the Jupyter notebook file (.ipynb) from your computer.

Mount Google Drive (if your data is stored on Google Drive):
from google.colab import drive
drive.mount('/content/drive')

Running the Code
Execute each cell in the notebook sequentially by pressing Shift + Enter.
To run all cells at once, you can use the Runtime > Run all option in the menu.

Data
This project uses a dataset that requires preprocessing steps like encoding and scaling. The dataset can be loaded directly into Google Colab using pandas:
train = pd.read_csv('/content/drive/MyDrive/Datasets/Train_data.csv')
test = pd.read_csv('/content/drive/MyDrive/Datasets/Test_data.csv')
     
Results
The results of the model evaluations are displayed in the notebook. These include:

Accuracy, Recall, ROC-AUC, F1 Score, Precision, FPR, and FNR for each model.
Visualizations of the above metrics for a comprehensive comparison.
