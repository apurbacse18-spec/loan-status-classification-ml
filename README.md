# Loan Status Classification using Machine Learning

## Overview

This project demonstrates a machine learning classification workflow for predicting loan status using historical loan data. The notebook applies multiple classification algorithms and compares their performance using evaluation metrics such as Jaccard score, F1-score, and Log Loss.

The project was completed as a machine learning practice project using the IBM/Cognitive Class loan classification dataset.

---

## Project Objective

The main objective of this project is to build and evaluate machine learning models that can classify whether a loan is likely to be paid off or go into collection based on customer and loan-related features.

---

## Dataset

The dataset contains historical loan records with features such as:

- Loan status
- Principal amount
- Loan terms
- Effective date
- Due date
- Age
- Education
- Gender

The dataset is downloaded directly inside the notebook.

---

## Machine Learning Models Used

The following classification models are implemented and compared:

1. K-Nearest Neighbors
2. Decision Tree
3. Support Vector Machine
4. Logistic Regression

---

## Workflow

The notebook follows this workflow:

1. Import required libraries
2. Download and load the dataset
3. Explore the dataset
4. Convert date fields
5. Perform data visualization
6. Preprocess categorical and numerical features
7. Apply one-hot encoding
8. Normalize the feature set
9. Train classification models
10. Evaluate models using a test dataset
11. Compare final results

---

## Model Evaluation

The models are evaluated using:

- Jaccard score
- F1-score
- Log Loss for Logistic Regression

Example final results from the notebook:

| Algorithm | Jaccard | F1-score | Log Loss |
|---|---:|---:|---:|
| KNN | 0.72 | 0.71 | N/A |
| Decision Tree | 0.74 | 0.63 | N/A |
| SVM | 0.74 | 0.63 | N/A |
| Logistic Regression | 0.78 | 0.76 | 0.67 |

Based on the recorded results, Logistic Regression achieved the strongest overall performance.

---

## Tools and Libraries

- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Repository Structure

```text
loan-status-classification-ml/
├── README.md
├── notebooks/
│   └── loan_status_classification_ml.ipynb
├── requirements.txt
└── .gitignore
