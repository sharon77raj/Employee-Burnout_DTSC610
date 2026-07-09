# Employee Burnout Prediction Using Machine Learning

## Project Overview

This project applies machine learning classification algorithms to predict employee burnout using a synthetic Human Resources dataset obtained from Kaggle.

The project compares multiple classification models before and after applying SMOTE to address class imbalance.

## Objectives

- Perform Exploratory Data Analysis (EDA)
- Preprocess employee data
- Address class imbalance using SMOTE
- Train and evaluate multiple classification models
- Compare model performance

## Dataset

Source:
https://www.kaggle.com/datasets/ankam6010/synthetic-hr-burnout-dataset

Target Variable:

- Burnout
  - 0 = No Burnout
  - 1 = Burnout

## Machine Learning Models

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gradient Boosting
- Naïve Bayes

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- imbalanced-learn
- Matplotlib
- Seaborn

## Project Structure

```
EmployeeBurnoutProject/
│
├── data/
├── notebooks/
├── reports/
├── README.md
```

## Results

Tree-based models (Decision Tree, Random Forest, and Gradient Boosting) achieved the highest predictive performance. Logistic Regression and Naïve Bayes showed improved recall after applying SMOTE.

## Author

Sharon Raj

Master of Data Science

New York Institute of Technology
