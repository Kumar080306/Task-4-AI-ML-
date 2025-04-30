Task-No.4
Binary Classifier with Logistic Regression

Objective

This project aims to build a binary classifier using Logistic Regression to classify data into two categories (0 or 1). We will use Python's Scikit-learn, Pandas, and Matplotlib libraries to train and evaluate the model.
Tools Used

Scikit-learn: For building and evaluating the Logistic Regression model.
Pandas: For handling and manipulating the dataset.
Matplotlib: For visualizing the results.
Steps Followed

Dataset:
A binary classification dataset is used for training the model.
The dataset contains features and a target variable (0 or 1).
Train/Test Split:
We split the dataset into two parts:
Training Set: For training the model.
Test Set: For evaluating the model.
Feature Standardization:
The features (input data) are standardized to make sure they all have a similar scale, which helps the model perform better.
Building the Model:
A Logistic Regression model is trained on the training data.
Evaluation:
The model's performance is evaluated using:
Confusion Matrix: To show the correct and incorrect classifications.
Precision and Recall: To measure the accuracy of the model.
ROC-AUC Curve: To visualize the model's performance.
Threshold Tuning:
We adjust the decision threshold of the classifier and explain how the sigmoid function works in this process.
Sigmoid Function

The sigmoid function is used in Logistic Regression to map predicted values (between 0 and 1). This function helps decide whether the output is 0 or 1 based on a threshold value.
