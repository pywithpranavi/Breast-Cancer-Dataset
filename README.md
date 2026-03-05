# Breast Cancer Classification using Machine Learning

## Project Overview
This project demonstrates how machine learning can be used to classify breast cancer tumors as malignant or benign. The dataset used in this project is the Breast Cancer dataset available in the Scikit-learn library.

## Objective
The main objective of this project is to build a machine learning model that can accurately predict whether a tumor is malignant (cancerous) or benign (non-cancerous) based on various medical features.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

## Dataset
The dataset used in this project is the Breast Cancer dataset provided by Scikit-learn using the load_breast_cancer() function.

The dataset contains several features such as:
- Mean radius
- Mean texture
- Mean perimeter
- Mean area
- Mean smoothness

These features help in determining whether a tumor is malignant or benign.

## Machine Learning Process
The following steps are implemented in this project:

1. Importing required libraries
2. Loading the dataset
3. Data preprocessing
4. Splitting the dataset into training and testing sets
5. Training the machine learning model
6. Evaluating model performance

## Example Code

from sklearn.datasets import load_breast_cancer

data = load_breast_cancer()

## Model Used
Logistic Regression / Classification Model

## Output
The model predicts whether the tumor is malignant or benign based on the input features.

## Conclusion
Machine learning models can assist in medical diagnosis by analyzing medical datasets and predicting disease outcomes with good accuracy.
