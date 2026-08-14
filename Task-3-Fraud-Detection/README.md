# Fraud Detection

## OASIS INFOBYTE Data Analytics Internship

### Level 1 - Task 3

## Objective

The objective of this project is to detect fraudulent financial
transactions using machine learning techniques.

## Dataset

The project uses the Credit Card Fraud Detection dataset from Kaggle.
The dataset contains credit card transactions with a highly
imbalanced distribution between normal and fraudulent transactions.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Google Colab

## Data Analysis

The dataset was explored to understand:

- Dataset structure
- Class distribution
- Fraudulent and non-fraudulent transactions
- Transaction amount distribution
- Fraud patterns by time

## Handling Class Imbalance

The dataset contains significantly fewer fraudulent transactions than
normal transactions.

SMOTE (Synthetic Minority Oversampling Technique) was used on the
training data to handle the class imbalance.

## Machine Learning Models

Two machine learning models were used:

1. Logistic Regression
2. Random Forest Classifier

## Model Evaluation

The models were evaluated using:

- Precision
- Recall
- F1 Score
- AUC-ROC

These metrics were selected because accuracy alone can be misleading
when working with highly imbalanced fraud detection data.

## Random Forest Results

The Random Forest model achieved:

- Precision: 0.827
- Recall: 0.827
- F1 Score: 0.827
- AUC-ROC: 0.964

## ROC Curve

An ROC curve was created to evaluate the model's ability to distinguish
between fraudulent and normal transactions.

## Feature Importance

Random Forest feature importance was analyzed to identify the features
that contributed most to fraud prediction.

## Conclusion

The project demonstrates how machine learning can be used to identify
fraudulent transactions. Handling class imbalance and using appropriate
evaluation metrics such as Precision, Recall, F1 Score and AUC-ROC are
important for building an effective fraud detection system.

The Random Forest model achieved an AUC-ROC of approximately 0.964,
showing strong discrimination between fraudulent and normal
transactions on the test data.

