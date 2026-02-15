# Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression

##  Dataset Used

- Dataset Name: Telecom Customer Churn Dataset
- File: data.csv
- Records: 7,000+ customers
- Features: 21 columns

**Target Variable:**
- Churn → Yes = 1, No = 0

## Dependencies

Install using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter


## Algorithm Used

### Logistic Regression

- Type: Supervised Machine Learning Algorithm
- Category: Binary Classification
- Purpose: Predict whether a customer will churn or not
- Output: Yes (Churn) / No (Not Churn)

**Why Logistic Regression?**
- Simple and easy to understand
- Works well for binary problems
- Fast training
- Provides interpretable results

## Techniques Used

- Data Cleaning (handling missing values)
- Data Type Conversion (string to numeric)
- One-Hot Encoding (pd.get_dummies())
- Feature Scaling (MinMaxScaler)
- Exploratory Data Analysis (EDA)
- Train-Test Split (70% Train, 30% Test)
- Model Training and Testing

**Purpose:**
These techniques improve data quality, make data suitable for ML models, and increase prediction accuracy.

## Model Performance

**Accuracy Achieved:**
- 80.75%

## Precision, Recall, and F1-Score

| Metric    | Value |
|-----------|--------|
| Precision | 72%    |
| Recall    | 64%    |
| F1-Score  | 68%    |

##  Conclusion

- The project successfully predicts telecom customer churn.
- Logistic Regression achieved good accuracy.
- Data preprocessing improved model performance.
- Visual analysis helped understand customer behavior.
- The model can help telecom companies reduce customer loss.

**Final Outcome:**
This project demonstrates strong understanding of machine learning fundamentals and practical implementation.
