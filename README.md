# TELCO-CUSTOMER_CHURN_ANALYSIS

This project focuses on analyzing customer churn for a telecom company using the Telco Customer Churn dataset. The goal is to identify key factors that influence customer churn and derive actionable insights using data analysis and visualization techniques.
The analysis is performed in a **Jupyter Notebook (.ipynb)** using Python and popular data science libraries.

## 📂 Dataset Information

* **Dataset Name:** Telco Customer Churn
* **Source:** IBM Sample Dataset
* **File Used:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`
* **Records:** 7,043 customers
* **Target Variable:** `Churn` (Yes / No)

### Key Features:

* Customer demographics (gender, senior citizen)
* Services used (internet, phone, streaming)
* Contract & billing details
* Monthly & total charges

## 🛠️ Tools & Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Data preprocessing & modeling (if applied)

## 🔍 Analysis Performed

* Data loading and inspection
* Handling missing and incorrect values
* Exploratory Data Analysis (EDA)
* Churn distribution analysis
* Impact of:

  * Contract type
  * Monthly charges
  * Tenure
  * Internet services
* Feature engineering
* Outlier handling
* Encoding categorical variables
* Machine learning model preparation and evaluation

## 📈 Key Insights

* Customers with **month-to-month contracts** have higher churn rates
* **Higher monthly charges** are strongly linked to churn
* **Long-tenure customers** are less likely to churn
* Customers using **fiber optic internet** churn more compared to DSL users

## 🎯 Use Cases

* Business decision-making for customer retention
* Churn prediction modeling
* Data analytics interview portfolio project
* Academic or internship project

## 📌 Future Improvements

* Build and compare ML models (Logistic Regression, Random Forest, XGBoost)
* Deploy churn prediction using Streamlit
* Add model explainability (SHAP / Feature Importance)
