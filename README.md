# Decision-Tree-Regression

**Decision Tree Classifier for Salary Prediction and Titanic Survival Analysis**
This repository contains code for training and evaluating Decision Tree Classifiers on two datasets: salary prediction and Titanic survival prediction. The goal is to demonstrate how to preprocess data, train a model, and make predictions using scikit-learn's DecisionTreeClassifier.

**Project Overview**

**Datasets**
Salaries Dataset (salaries (1).csv)
Contains information about employees, including their company, job title, and degree.
The target variable is whether an employee's salary exceeds $100,000.

Titanic Dataset (titanic.csv)
Contains information about Titanic passengers, including their age, sex, and whether they survived.
The target variable is survival status (0 for not survived, 1 for survived).

**Tasks**
**Salary Prediction**
Preprocess the data by encoding categorical variables.
Train a Decision Tree Classifier to predict if an employee's salary is greater than $100,000.
Evaluate the model’s accuracy.

**Titanic Survival Prediction**
Preprocess the data by handling missing values and encoding categorical variables.
Train a Decision Tree Classifier to predict survival on the Titanic.
Evaluate the model’s accuracy.

**Setup and Requirements**

**Dependencies**
pandas
scikit-learn

**Data Files**
salaries (1).csv: For salary prediction.
titanic.csv: For Titanic survival prediction.

**Code Walkthrough**
**Salary Prediction**
**Load and Prepare Data**
Read the CSV file.
Extract features and target variable.

**Preprocess Data**
Encode categorical variables using LabelEncoder.
Drop original categorical columns.

**Train and Evaluate Model**
Train a DecisionTreeClassifier model.
Evaluate the model accuracy.
Make predictions.

**Titanic Survival Prediction**
**Load and Prepare Data**
Read the CSV file.
Drop irrelevant columns.

**Preprocess Data**
Handle missing values.
Encode categorical variables.

**Train and Evaluate Model**
Split data into training and testing sets.
Train a DecisionTreeClassifier model.
Evaluate the model accuracy.
Make predictions.
