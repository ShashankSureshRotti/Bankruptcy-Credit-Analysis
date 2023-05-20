# Bankruptcy-Credit-Analysis
Performed Exploratory Data Analysis, Data pre-processing, feature engineering and applied several Machine learning algorithms to classify whether a company will go bankrupt.

## Introduction
This project aims to classify whether companies are likely to go bankrupt based on their financial data. The analysis is performed on the financials of the company, and various machine learning algorithms are applied to predict bankruptcy. The project includes exploratory data analysis, feature engineering using techniques like PCA (Principal Component Analysis), and evaluation of different machine learning algorithms to select the best performing model.

## Dataset
The dataset used for this project consists of financial features of different companies. Each company is labeled as either bankrupt or not bankrupt. The dataset includes relevant financial indicators such as liquidity ratios, profitability ratios, leverage ratios, and other metrics that provide insights into a company's financial health.

## Exploratory Data Analysis
Exploratory data analysis is performed on the dataset to gain a better understanding of the variables and their relationships. This step includes data cleaning, handling missing values, and examining the distribution of each feature. Visualizations such as histograms, box plots, and correlation matrices are utilized to identify patterns and potential outliers in the data.

## Feature Engineering
Feature engineering is a crucial step in building an effective machine learning model. In this project, feature engineering techniques are applied to identify the features that contribute the most to the classification task. Principal Component Analysis (PCA) is utilized to reduce the dimensionality of the dataset while retaining the most important information. This technique helps in capturing the variance within the data and selecting the principal components that have the highest impact on the classification task.

## Machine Learning Algorithms
Several machine learning algorithms are implemented and evaluated to predict the bankruptcy status of companies. The algorithms used in this project include:

1. Logistic Regression
2. Support Vector Machine (SVM)
3. K-Nearest Neighbors (KNN)
4. Random Forest
Evaluation metrics such as accuracy and recall rate are used to assess the performance of each algorithm. Given the importance of recall rate for the project, Random Forest is selected as the best performing model due to its high recall rate and overall accuracy.

## Conclusion
This project demonstrates the application of exploratory data analysis, feature engineering, and various machine learning algorithms to classify whether companies will go bankrupt or not. By utilizing techniques like PCA and evaluating different models, the Random Forest algorithm is identified as the best performing classifier for this task, considering its high recall rate and accuracy. The results and insights obtained from this project can be valuable for investors, financial institutions, and other stakeholders to make informed decisions regarding company bankruptcy risk.
