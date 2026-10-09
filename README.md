# Credit Card Fraud Detection

A machine learning classification project that identifies fraudulent credit card transactions in a highly imbalanced dataset.

## Models

* Logistic Regression
* XGBoost
* LightGBM
* Class-imbalance handling and model comparison

## Best Model: Balanced XGBoost

Evaluated on a held-out test set:

| Metric    |  Score |
| --------- | -----: |
| Precision | 97.37% |
| Recall    | 77.89% |
| F1-Score  | 86.55% |
| ROC-AUC   | 97.28% |

The model detected 74 of 95 fraudulent transactions, with 2 false positives.

## Tech Stack

Python, Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, Matplotlib, Seaborn, Joblib.

## Project Workflow

Data cleaning, exploratory data analysis, preprocessing, model training, evaluation, class-imbalance handling, and model serialization.

## Run Locally

1. Clone this repository.
2. Install the required dependencies.
3. Open `Fraud_Detection_ML.ipynb` in Jupyter Notebook.
4. Download the dataset separately and place `creditcard.csv` in the project directory.

## Dataset

Credit Card Fraud Detection dataset. The dataset is excluded from this repository; obtain it from Kaggle.

## Author
Agboola Kehinde Oluwaseun (FlyVark AI)
