## Project overview
This project builds an **Artificial Neural Network (ANN)** to predict whether a telecom customer is likely to **churn** or **stay** based on customer account information, services used, and billing behavior.

The notebook walks through the complete machine learning workflow:
- loading and cleaning customer churn data
- exploring patterns related to churn
- encoding categorical features into numeric form
- scaling numerical variables
- splitting the data into training and testing sets
- training a neural network using TensorFlow/Keras
- evaluating results using accuracy, confusion matrix, precision, recall, and F1-score
- Using dropout regularization to improve accuracy accuracy, confusion matrix, precision, recall, and F1-score.
- Used Oversampling, Undersampling, and SMOTE technique to correct the imbalance for the dataset.

## What this project is trying to do
The main goal is to create a classification model that can help a business identify:
- which customers are at risk of leaving
- what customer patterns are associated with churn
- how to use historical customer data to make retention decisions

In practical terms, this kind of model can support:
- customer retention campaigns
- targeted offers for high-risk customers
- reduction in lost revenue due to churn
- better understanding of service and billing factors that influence customer behavior

## Dataset used
The notebook uses a dataset named:
- `customer_churn.csv`

From the code, the dataset appears to include features such as:
- customer ID
- gender
- tenure
- monthly charges
- total charges
- phone/internet-related service features
- churn label (`Yes` / `No`)
