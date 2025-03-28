# Breast Cancer Classification Project

This project aims to evaluate the performance of various supervised learning classification algorithms in predicting breast cancer diagnosis using the scikit-learn (sklearn) breast cancer dataset.

## Project Description

The objective of this project is to implement and compare five classification algorithms:

1.  Logistic Regression
2.  Decision Tree Classifier
3.  Random Forest Classifier
4.  Support Vector Machine (SVM)
5.  k-Nearest Neighbors (k-NN)

The project includes data loading, preprocessing, model implementation, and performance evaluation.

## Dataset

The project uses the breast cancer dataset available in the sklearn library.

## Project Structure

## Data loading

*Load the dataset from breast cancer dataset available in the sklearn library.

## Preprocessing Steps

* **Loading the Dataset:** The breast cancer dataset is loaded from sklearn.
* **Missing Value Handling:** The dataset is checked for missing values.
* **Feature Scaling (Standardization):** The features are standardized using `StandardScaler` to ensure they have a mean of 0 and a standard deviation of 1.
* **Train-Test Split:** The dataset is split into training (80%) and testing (20%) sets.

## Classification Algorithms Implemented

* **Logistic Regression:** A linear model for binary classification.
* **Decision Tree Classifier:** A tree-based model that makes decisions based on feature values.
* **Random Forest Classifier:** An ensemble of decision trees.
* **Support Vector Machine (SVM):** A model that finds the optimal hyperplane to separate classes.
* **k-Nearest Neighbors (k-NN):** A model that classifies data points based on their nearest neighbors.

## Model Evaluation

The performance of each algorithm is evaluated using accuracy and a classification report (precision, recall, F1-score).

## Results

* **Best Performing Model:** SVM
* **Worst Performing Model:** Decision Tree Classifier and KNN

## Files

*Breast_cancer_classification.ipynb
*README.md
