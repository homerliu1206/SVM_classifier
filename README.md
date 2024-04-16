# SVM Classifier for Predictive Analysis

## Overview

This Python script analyzes three different datasets using Support Vector Machine (SVM) classifier to predict the likelihood of specific outcomes based on various input features. The script aims to provide predictive insights for different scenarios, including flight delays, task completion by employees, and loan approval by a bank.

## Datasets and Target Variables

### 1. Flight Delay Prediction
- **Target Variable:** `status_delayed`
- **Background:** The dataset provided by the airline contains information about flight delays, including factors such as departure time, day of the week, and weather conditions. The goal is to predict the likelihood of flight delays for future flights based on these factors.

### 2. Employee Task Completion Prediction
- **Target Variable:** `task_completed`
- **Background:** The HR department provides employee information, including experience level and training levels, to predict whether employees can complete assigned tasks. By analyzing these factors, HR aims to make better decisions about team assignments.

### 3. Loan Approval Prediction
- **Target Variable:** `approved`
- **Background:** A regional bank wants to predict loan approval based on customer data such as gender, age, occupation, and marital status. By analyzing past customer data, the bank aims to streamline the loan approval process and improve decision-making.

## Features

1. **Data Analysis:** The script analyzes each dataset to understand its structure, features, and target variable.
2. **Data Preprocessing:** It preprocesses the data by handling missing values, encoding categorical variables, and splitting the dataset into training and testing subsets.
3. **Model Training:** Utilizing SVM classifier, the script trains a predictive model on the training data to learn patterns and relationships between input features and target variables.
4. **Model Evaluation:** The trained model's performance is evaluated on the testing data using metrics such as accuracy, precision, recall, and F1-score.
5. **Prediction:** Finally, the script makes predictions on new data to forecast the likelihood of specific outcomes in future scenarios.
