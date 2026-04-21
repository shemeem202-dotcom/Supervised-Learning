# Breast-Cancer-Data-Analyis
## Overview

This project applies multiple supervised machine learning algorithms to classify breast cancer tumors as malignant or benign using the Breast Cancer dataset from sklearn.

The goal is to compare different models and evaluate their performance.

## Dataset
Source: sklearn.datasets.load_breast_cancer
Features: 30 numerical features (e.g., radius, texture, perimeter, area)
## Target:
* 0 → Malignant
* 1 → Benign
* Technologies Used
* Python
* Pandas & NumPy
* Scikit-learn
* Data Preprocessing
* Removed duplicate records
* Checked for missing values (none found)
* Split dataset:
* 80% Training
* 20% Testing
* Feature scaling applied using StandardScaler (for models sensitive to scale)
* Models Implemented

The following algorithms were trained and evaluated:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Evaluation Metrics
* Accuracy Score
* Classification Report
*  Confusion Matrix
## Results

Each model was trained and tested, and accuracy scores were compared to determine the best-performing algorithm.

(You can add your actual accuracy values here for better impact)

## Example:

* Logistic Regression Accuracy: XX%
* Decision Tree Accuracy: XX%
* Random Forest Accuracy: XX%
* SVM Accuracy: XX%
* KNN Accuracy: XX%
* Key Insights
* Feature scaling significantly improves performance for SVM and KNN
* Ensemble models like Random Forest often provide strong accuracy
* Model performance varies depending on data characteristics
* How to Run

Install required libraries:

pip install pandas numpy scikit-learn

Run the notebook:

jupyter notebook
Open the .ipynb file and execute all cells
Future Improvements
Hyperparameter tuning (GridSearchCV)
Cross-validation
Feature selection techniques
Model deployment (Flask / Streamlit)

 Author
Mohammed Shameem
AI & Data Science Student
