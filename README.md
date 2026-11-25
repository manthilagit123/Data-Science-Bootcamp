# Data-Science-Bootcamp
# Telco Customer Churn Prediction & Retention Analysis

An end-to-end Data Science capstone project completed as part of the **Codomax Data Science Internship**, covering data preprocessing, exploratory data analysis (EDA), business dashboarding, and supervised machine learning.

## Project Workflow
1. **Data Cleaning & Preprocessing:** Handled missing values in `TotalCharges` using median imputation and engineered binary target labels across 7,043 customer records.
2. **Exploratory Data Analysis (EDA):** Built a 4-panel visual dashboard analyzing churn rates across contract types, monthly charges, and customer tenure.
3. **Predictive Modeling:** Trained and evaluated a **Random Forest Classifier** using Scikit-learn (~80% accuracy), extracting Confusion Matrix metrics and Top 10 Feature Importances.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Environment:** Google Colab

## Key Business Takeaways
* **Month-to-Month contracts** carry the highest churn risk (~42.7%) compared to Two-Year contracts (~2.8%).
* **Tenure, Total Charges, and Monthly Charges** are the top predictors of customer churn, highlighting the importance of early customer onboarding and contract upgrade incentives.
