# IPL Auction Price Prediction

This project focuses on predicting the auction prices of players in the Indian Premier League (IPL) based on various features such as their performance statistics and roles.

## Introduction
This project utilizes machine learning techniques to predict the auction prices of players participating in the IPL. It involves data cleaning, preprocessing, feature selection, and model building to achieve accurate predictions.

## Getting Started

### Data Source
The data used in this project was scraped from ESPN Cricinfo, a leading sports website providing comprehensive coverage of cricket tournaments worldwide. The data was then cleaned and preprocessed to ensure its suitability for analysis and model building.

### Dependencies

The following libraries have been used in this project:
pandas, numpy, matplotlib, scikit-learn

### Code Overview
The code provided consists of the following main sections:

* Data Loading and Cleaning: Loading the IPL player data and performing initial cleaning.
* Categorical Data Preparation: Converting the salary column into categories for analysis.
* Modeling the Data: Building machine learning models to predict player auction prices.
* Feature Selection:
    *  Principal Component Analysis (PCA): Reducing dimensionality for feature selection.
    * Lasso Regression: Identifying significant features using L1 regularization.
* Evaluation: Evaluating the performance of models using accuracy and area under the curve (AUC) metrics.

### Results
The models are evaluated based on accuracy and AUC scores. Different machine learning algorithms such as Logistic Regression, Decision Trees, Random Forest, K-Nearest Neighbors, Support Vector Classifier, and Linear Discriminant Analysis are utilized for prediction.
