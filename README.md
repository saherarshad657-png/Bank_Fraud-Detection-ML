# Bank Fraud Detection Using Machine Learning

## Project Overview

This project focuses on detecting fraudulent financial transactions using machine learning techniques. The objective is to identify suspicious transactions and evaluate classification models on an imbalanced financial dataset.

## Objectives

* Clean and preprocess transaction data
* Analyze patterns associated with fraudulent transactions
* Prepare features for machine learning
* Handle class imbalance using SMOTE
* Train and compare machine learning models
* Evaluate model performance using precision, recall, F1-score, and accuracy

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Imbalanced-learn
* Jupyter Notebook

## Machine Learning Workflow

1. Data loading
2. Data cleaning and preprocessing
3. Exploratory data analysis
4. Feature preparation
5. Train-test split
6. Handling class imbalance using SMOTE
7. Model training
8. Model evaluation
9. Model comparison

## Models Used

### Random Forest

Random Forest was used to classify transactions as normal or fraudulent.

### XGBoost

XGBoost was also trained and evaluated for the fraud classification task.

## Evaluation Metrics

The models were evaluated using:

* Precision
* Recall
* F1-score
* Accuracy
* Confusion Matrix

Because fraud detection involves an imbalanced dataset, particular attention was given to the performance of the fraud class.

## Future Improvements

* Add more data visualizations
* Develop an interactive dashboard
* Perform hyperparameter tuning
* Experiment with additional machine learning models
* Deploy the model as a web application or API
* Explore real-time fraud detection

## Project Structure

```text
Bank-Fraud-Detection-ML/
│
├── Bank_Fraud_Detection.ipynb
└── README.md
```

## Disclaimer

This project is intended for educational and portfolio purposes and does not represent a production financial fraud detection system.
