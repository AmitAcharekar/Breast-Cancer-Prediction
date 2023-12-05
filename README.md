# Breast-Cancer-Prediction

## Description
This project aims to predict breast cancer using logistic regression based on data from the Breast Cancer Wisconsin (Diagnostic) Dataset.

## Steps Involved
## Data Collection & Processing
The breast cancer dataset is loaded using scikit-learn.
The data includes attributes like mean radius, mean texture, mean perimeter, and more.

## Data Preprocessing
The dataset is processed by creating a DataFrame and saving it as a CSV file for further use.
The 'target' column is added to the DataFrame.

## Model Building
The dataset is divided into features (X) and target labels (Y).
The data is split into training and testing sets.
Logistic Regression model is trained using the training data.

## Model Evaluation
The model is evaluated using the test dataset, and predictions are made.
Evaluation metrics like confusion matrix and accuracy score are used to assess the model's performance.
