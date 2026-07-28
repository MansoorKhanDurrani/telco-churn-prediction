# Telco Customer Churn Analysis

## Project Overview

This project predicts customer churn using the Telco Customer Churn dataset. The objective is to analyze customer behavior, identify factors contributing to churn, and build machine learning models that help businesses retain customers.

---

## Dataset

- **Dataset:** Telco Customer Churn Dataset
- **Source:** IBM Sample Dataset / Kaggle
- **Records:** 7,032
- **Features:** 25 input features and 1 target variable (`Churn`)

The dataset contains customer demographics, subscribed services, billing information, contract details, and churn status.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

---

## Project Workflow

1. Project Setup
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Data Preprocessing
7. Model Building
8. Model Evaluation
9. Business Recommendations
10. Conclusion

---

## Feature Engineering

The following five new features were created:

- TenureGroup
- AverageMonthlySpend
- TotalServices
- IsLongTermCustomer
- HasStreamingServices

These features improve the model's ability to capture customer loyalty, spending behavior, and service usage.

---

## Machine Learning Models

Two machine learning models were trained and evaluated:

- Logistic Regression
- Random Forest Classifier

---

## Results

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | **78.82%** |
| Random Forest | **78.96%** |

Although Random Forest achieved slightly higher accuracy, Logistic Regression showed better recall for churn prediction and was selected as the preferred model for this project.

---

## Business Insights

Key findings from the analysis include:

- Customers with month-to-month contracts are more likely to churn.
- Fiber optic customers have a higher churn rate.
- New customers are more likely to leave than long-term customers.
- Customers using more services generally show better retention.

---

## Data Quality Issues

During data exploration, the following issues were identified:

- The `TotalCharges` column was stored as an object instead of a numeric type.
- Missing values were present in the `TotalCharges` column.
- These missing values were removed after converting the column to numeric format.
- No duplicate records were found.

---

## Limitations

- The dataset represents historical customer behavior and may not reflect future trends.
- Only two machine learning models were evaluated.
- No hyperparameter tuning or cross-validation was performed.
- The model is intended as a baseline solution rather than a production-ready system.

---

## Future Improvements

Possible future enhancements include:

- Hyperparameter tuning
- Cross-validation
- Additional feature engineering
- Testing advanced models such as XGBoost and LightGBM
- Deploying the model using Flask or Streamlit

---

## Repository Structure

```
telco-customer-churn-analysis/
│
├── data/
│   └── Telco-Customer-Churn.csv
│
├── notebooks/
│   └── Customer_Churn_Analysis.ipynb
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

## Author

**Mansoor Khan**

BS Software Engineering

Machine Learning and Data Science Project
