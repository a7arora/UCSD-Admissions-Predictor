# UCSD-Admissions-Predictor
This project implements a logistic regression model to predict UCSD admissions based on two features: Unweighted GPA and Number of AP/IB/CC Courses. The dataset includes both admitted and non-admitted students, with the target variable being Accepted.

Key Details:

Features Used:

Unweighted GPA

Number of AP/IB/CC Courses

Model: Logistic Regression

Evaluation Metrics: Accuracy, Confusion Matrix, and Classification Report

Performance Summary:

Accuracy: 69.57%

Confusion Matrix:

True Negatives (0): 1

False Positives (0): 7

False Negatives (1): 0

True Positives (1): 15

Classification Report:

Precision for class '0' (Not Accepted): 1.00

Recall for class '1' (Accepted): 1.00

F1-Score for class '1' (Accepted): 0.81

Insights:
The model demonstrates high recall for predicting accepted students but struggles with predicting non-accepted students, as evidenced by the low recall for class '0'. This imbalance in performance could be due to the limited feature set, the inherent distribution of accepted vs. non-accepted students, or insufficient data preprocessing.

Data:
Dataset: UCSD Admissions Data (CSV format)

Model: Scikit-learn’s Logistic Regression
