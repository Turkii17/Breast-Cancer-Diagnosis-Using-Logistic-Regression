# Breast Cancer Diagnosis Using Logistic Regression

# Introduction
This repository contains code for a breast cancer diagnosis model using logistic regression. It also includes a custom implementation of logistic regression for educational purposes. The dataset used is 'BCdata.csv,' and the code is written in Python, utilizing popular libraries such as NumPy, Pandas, Matplotlib, and Seaborn.

# Data Preprocessing
The initial steps involve loading the dataset ('BCdata.csv'), dropping unnecessary columns, and encoding the diagnosis labels ('M' for malignant and 'B' for benign) into binary values (1 for malignant, 0 for benign). The dataset is then split into features (X) and labels (Y).

# Logistic Regression with Scikit-Learn
A logistic regression model is trained using Scikit-Learn's LogisticRegression class. The model is evaluated on a test set, and predictions are compared with actual labels. The coefficient of determination (R² score) is calculated to assess the model's performance.

# Custom Logistic Regression Implementation
A custom implementation of logistic regression is provided, including functions for sigmoid activation, loss calculation, gradient computation, and model training. The data is normalized, and stochastic gradient descent (SGD) is employed for optimization. The training process returns the learned weights, bias, and a list of losses over epochs.

# Model Evaluation
The custom implementation is evaluated on the test set, and accuracy is calculated using the trained model. A confusion matrix is generated using Seaborn's heatmap to visualize the model's performance.

# Prediction Example
A sample input for predicting breast cancer diagnosis is provided, demonstrating how to use the trained custom logistic regression model for predictions.
