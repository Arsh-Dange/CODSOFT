# Credit Card Fraud Detection

## Project Overview
This project uses Machine Learning to identify fraudulent credit card transactions. 
The objective is to classify transactions as either genuine or fraudulent by analyzing transaction-related features.
The model is trained using historical transaction data and evaluated on unseen test data.

## Objective
Build a Machine Learning model that can detect fraudulent credit card transactions with high accuracy.

## Dataset
Dataset Files
 fraudTrain.csv
 fraudTest.csv

Target Variable
 is_fraud

Values
 0 = Genuine Transaction
 1 = Fraudulent Transaction

## Technologies Used
 Python
 Google Colab
 Pandas
 NumPy
 Matplotlib
 Scikit-learn

## Steps Performed
1. Imported the required libraries.
2. Loaded training and testing datasets.
3. Performed data exploration.
4. Checked missing values.
5. Analyzed fraud distribution.
6. Removed unnecessary columns.
7. Encoded categorical variables.
8. Trained a Logistic Regression model.
9. Evaluated model performance.
10. Visualized the confusion matrix.

## Evaluation Metrics
 Accuracy Score
 Classification Report
 Confusion Matrix

## Project Structure
Task2_Credit_Card_Fraud_Detection
│── Credit_Card_Fraud_Detection.ipynb
│── README.md
└── screenshots
  │── train_dataset_shape.png
  │── missing_values.png
  │── fraud_distribution.png
  │── accuracy.png
  │── classification_report.png
  └── confusion_matrix.png

## Conclusion
The Machine Learning model successfully detects fraudulent transactions by learning patterns from historical data. 
This project demonstrates the practical application of Machine Learning in financial fraud prevention systems.
