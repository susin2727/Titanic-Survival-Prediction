# Titanic Survival Prediction Using Machine Learning

## Overview

This project predicts whether a passenger survived the Titanic disaster using Machine Learning techniques.

The project demonstrates the complete machine learning workflow, including:

* Data Cleaning
* Feature Engineering
* Data Preprocessing
* Model Training
* Model Evaluation
* Performance Visualization

## Dataset

Titanic Dataset from Kaggle

Features used:

* Pclass
* Sex
* Age
* SibSp
* Parch
* Fare
* Embarked

Target Variable:

* Survived (0 = No, 1 = Yes)

## Data Preprocessing

* Removed Cabin column due to excessive missing values.
* Filled missing Age values using median.
* Filled missing Embarked values using mode.
* Encoded categorical variables (Sex and Embarked).
* Removed irrelevant columns (PassengerId, Name, Ticket).
  
## Machine Learning Algorithms

### Decision Tree Classifier

Accuracy: 79.0%

### Random Forest Classifier

Accuracy: 79.89%

AUC Score: 0.8951

## Results

| Model         | Accuracy |
| ------------- | -------- |
| Decision Tree | 79.0%    |
| Random Forest | 79.89%   |

## Evaluation Metrics

* Accuracy Score
* Confusion Matrix
  <img width="530" height="455" alt="confusion_matrix" src="https://github.com/user-attachments/assets/47a86d8f-69e2-452e-ab2d-c0eb04bcffbb" />

* Classification Report
* ROC Curve
  
  <img width="536" height="393" alt="roc_curve" src="https://github.com/user-attachments/assets/65f5f725-c52c-43e7-abc8-8d4cb887a8a0" />

* AUC Score

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

## Key Learnings

- Data Cleaning
- Handling Missing Values
- Feature Engineering
- Supervised Learning
- Model Evaluation
- ROC Curve Analysis
  
## Project Outcome

The Random Forest model achieved the best performance with an accuracy of 79.89% and an AUC score of 0.8951, demonstrating strong predictive capability for Titanic survival prediction.
