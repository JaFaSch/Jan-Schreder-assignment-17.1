# Jan-Schreder-assignment-17.1
Practical Application Assignment 17.1: Comparing Classifiers
# Bank Marketing Campaign Analysis

## Overview

This repository contains an analysis of the effectiveness of various marketing campaigns conducted by a Portuguese banking institution. The primary objective is to predict whether clients will subscribe to a term deposit based on multiple telemarketing efforts. Understanding this prediction is crucial for the bank as it directly impacts their marketing strategies and customer engagement.

By identifying the characteristics of clients most likely to accept the offer, the bank can optimize its marketing efforts, allocate resources more effectively, and tailor communications to specific customer segments. This approach enhances customer satisfaction through personalized offerings and increases the overall profitability of the bank by reducing wasted marketing expenditures.

## Business Problem

The key business problem addressed in this analysis is to predict client subscription to a term deposit. This problem-solving will enable the bank to make data-driven decisions that improve targeting potential clients, ultimately leading to higher conversion rates in their marketing campaigns.

## Data Understanding and Preparation

The dataset used in this analysis is sourced from a bank's marketing campaign and includes various features such as client demographics, previous contact results, and campaign details. 

### Key Steps in Data Preparation:
1. **Data Loading**: The dataset is loaded from a CSV file.
2. **Data Cleaning**: Irrelevant columns are dropped, missing values are removed, and 'unknown' entries are filtered out.
3. **Encoding**: Binary variables are mapped to 0 and 1, and categorical variables are one-hot encoded.
4. **Train-Test Split**: The data is split into training and testing sets for model evaluation.

## Modeling

The analysis involves training multiple classification models, including:

- **K-Nearest Neighbors (KNN)**: Classifies based on the majority class among neighbors.
- **Logistic Regression**: Predicts binary outcomes using a logistic function.
- **Decision Tree**: Splits data into subsets to create a tree-like model.
- **Support Vector Machine (SVM)**: Finds the optimal hyperplane that maximizes class separation.

### Hyperparameter Tuning
Models undergo hyperparameter tuning using techniques like GridSearchCV and HalvingRandomSearchCV to optimize performance.

## Evaluation

Model performance is evaluated using accuracy, precision, recall, and F1-score metrics. A confusion matrix is also generated for each model to visualize classification results.

### Visualization
Training times and performance metrics are visualized using bar plots for easy comparison of model effectiveness.

## Requirements

To run the code in this repository, ensure you have the following Python packages installed:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

Contact
For any inquiries or feedback, feel free to reach out via GitHub.
