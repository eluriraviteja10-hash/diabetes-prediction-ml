Diabetes Prediction using Machine Learning

This is a healthcare-focused Machine Learning project that predicts whether a patient is diabetic based on clinical features such as glucose level, BMI, insulin, blood pressure, and age.

Project Overview

This project demonstrates an end-to-end ML pipeline:

Data loading

Data cleaning (handling invalid medical values)

Exploratory Data Analysis

Feature scaling

Train-test split

Logistic Regression

Random Forest (tuned)

Confusion matrix + classification report

🩺 Dataset

Public diabetes dataset (PIMA Indians Diabetes Database):
https://raw.githubusercontent.com/plotly/datasets/master/diabetes.csv

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Google Colab

Model Performance

Logistic Regression: ~75% accuracy

Tuned Random Forest: ~75–78% accuracy

Key Insights

Glucose is the most significant predictor

BMI and age also correlate with diabetes

Healthcare models must balance recall and false negatives

Healthcare Relevance

This model can help identify high-risk diabetic patients early, enabling healthcare providers to recommend timely checkups and treatments.

Files in this repository

Diabetes_Prediction_Project.ipynb — Full Python notebook

README.md — Project explanation
