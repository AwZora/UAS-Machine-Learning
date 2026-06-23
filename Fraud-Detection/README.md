# Fraud Detection Project

## Project Purpose

This project aims to build an end-to-end fraud detection pipeline using transaction data to predict whether an online transaction is fraudulent or not.

## Dataset

Dataset: train_transaction.csv

- Total samples: 590,540 transactions
- Total features: 394 columns
- Target variable: isFraud

## Workflow

1. Data Loading
2. Data Exploration
3. Missing Value Handling
4. Feature Engineering
5. Data Preprocessing
6. Class Imbalance Handling
7. Model Training
8. Hyperparameter Tuning using Optuna
9. Model Evaluation
10. MLflow Tracking

## Model Used

- Random Forest Classifier

## Evaluation Results

The model was evaluated using classification metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

Detailed results can be found in:

```text
fraud_detection.ipynb
```

## Hyperparameter Tuning

Optuna was used to search for the best model parameters and improve classification performance.

## MLflow Tracking

MLflow was used to track:

- Model parameters
- Evaluation metrics
- Experiment results

## Repository Structure

```text
Fraud-Detection/
│
├── fraud_detection.ipynb
├── README.md
```

## Student Information

Name: Dony Tri Nugroho

NIM: 11103202041

Class: TK-46-GABUNGAN
