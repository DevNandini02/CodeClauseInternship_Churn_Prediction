# CodeClauseInternship_Churn_Prediction
# Telecom Churn Prediction Model using Logistic Regression

# Overview
This repository contains a churn prediction model tailored for the telecom industry. Churn prediction is a critical task for telecom companies to identify customers at risk of leaving their services. The model is built using logistic regression, a common technique for binary classification problems.

# Dataset
The dataset used for training and testing the model was obtained from Kaggle.Link for the dataset is given below.
Link:https://www.kaggle.com/datasets/abhinav89/telecom-customer

This data set consists of 100 variables and approx 100 thousand records. It contains different variables explaining the attributes of telecom industry and various factors considered important while dealing with customers of telecom industry. The target variable here is churn which explains whether the customer will churn or not.

# Preprocessing 
The prepocessing steps for this model includes:
1. Dropping rows with missing values
2. Label Encoding
3. Standard scaling

# Algorithm used
We instantiated a logistic regression model with the following parameters:
- `random_state`: 42 (for reproducibility)
- `max_iter`: 1000 (maximum number of iterations for optimization)
  
# Model Performance
The model achieved an accuracy of 0.59 and a precision of 0.57.

# Dependencies
The following Python libraries and modules are required to run this project:

- [pandas](https://pandas.pydata.org/): Used for data manipulation and analysis.
- [scikit-learn](https://scikit-learn.org/stable/): Provides tools for machine learning, including model selection and preprocessing.
- [numpy](https://numpy.org/): Used for numerical operations and data manipulation.
- [matplotlib](https://matplotlib.org/): Used for data visualization (if applicable).

You can install these dependencies using `pip` with the following command:
```bash
pip install pandas scikit-learn numpy matplotlib
