# End-to-End ML Pipeline for Customer Churn Prediction

## Project Overview

This project was completed as part of the **DevelopersHub Corporation AI/ML Engineering Advanced Internship**.

The objective of this project is to build a reusable and production-ready machine learning pipeline that predicts whether a telecom customer is likely to churn. The complete workflow includes data preprocessing, model training, hyperparameter tuning, evaluation, and exporting the trained pipeline for future use.

---

## Objective

- Build an end-to-end machine learning pipeline using Scikit-learn Pipeline API.
- Automate data preprocessing using ColumnTransformer.
- Train and compare multiple machine learning models.
- Optimize model performance using GridSearchCV.
- Export the final trained pipeline using Joblib.

---

## Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains customer demographic information, subscribed services, account details, and a target variable (**Churn**) indicating whether a customer has left the company.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Matplotlib

---

## Project Workflow

1. Import required libraries.
2. Load and explore the dataset.
3. Perform data preprocessing.
4. Handle missing values.
5. Encode categorical variables.
6. Split the dataset into training and testing sets.
7. Build preprocessing pipelines using ColumnTransformer.
8. Train Logistic Regression and Random Forest models.
9. Optimize Random Forest using GridSearchCV.
10. Evaluate model performance.
11. Save the trained pipeline using Joblib.

---

## Models Used

- Logistic Regression
- Random Forest Classifier

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Classification Report
- Confusion Matrix

---

## Results

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | **80.55%** |
| Optimized Random Forest | **79.99%** |

The Logistic Regression model achieved the highest accuracy on the test dataset.

---

## Repository Contents

```
Task-2-End-to-End-ML-Pipeline/
│
├── README.md
├── Task_2_End_to_End_ML_Pipeline.ipynb
└── customer_churn_pipeline.pkl
```

---

## How to Run

1. Open the notebook in Google Colab.
2. Install the required libraries if needed.
3. Run all notebook cells in sequence.
4. The trained pipeline will be saved as:

```
customer_churn_pipeline.pkl
```

---

## Key Learnings

- Scikit-learn Pipeline API
- ColumnTransformer
- Data preprocessing
- Feature engineering
- Hyperparameter tuning using GridSearchCV
- Model evaluation
- Model serialization using Joblib

---

## Future Improvements

- Experiment with XGBoost and LightGBM.
- Perform advanced feature engineering.
- Deploy the trained pipeline using Streamlit.
- Build an interactive web application.

---

## Author

**Muhammad Ahmad**

Software Engineering Student

AI/ML Enthusiast | .NET Developer | Machine Learning
