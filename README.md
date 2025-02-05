# MBA Admission Prediction

## Overview
This project predicts MBA admission chances based on applicant details using multiple machine learning models. The goal is to analyze how factors like GPA, GMAT score, work experience, and major influence admission decisions.

## Features
- Data preprocessing and feature engineering.
- Comparison of different ML models for admission prediction.
- Performance evaluation using accuracy, confusion matrix, and classification reports.
- Deep learning model implementation using TensorFlow/Keras.
- Data visualization for better insights.

## Tech Stack
- Python
- Pandas, NumPy (Data Handling)
- Scikit-learn (Machine Learning)
- TensorFlow/Keras (Deep Learning)
- Seaborn, Matplotlib (Visualization)

## Dataset
The dataset consists of various attributes related to MBA applicants:

| Column Name         | Description |
|---------------------|-------------|
| application_id      | Unique ID for each applicant |
| gender             | Gender of the applicant |
| international      | Whether the applicant is an international student (True/False) |
| gpa               | Grade Point Average |
| major             | Undergraduate major |
| race              | Ethnicity of the applicant |
| gmat              | GMAT score |
| work_exp          | Years of work experience |
| work_industry     | Industry where the applicant worked |
| admission         | Admission result (Accepted/Rejected) |

## Models Used
1. Decision Tree Classifier
2. Random Forest Classifier
3. Naïve Bayes (GaussianNB)
4. Deep Learning Model (Neural Network)
