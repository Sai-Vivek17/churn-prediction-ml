# 📊 Telco Customer Churn Prediction

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Project Overview
Retaining customers is often more cost-effective than acquiring new ones. This project focuses on analyzing customer behavior within a telecommunications company to predict **Churn** (whether a customer will leave the service). By identifying high-risk customers, the business can implement targeted retention strategies.

## 🗂️ Dataset
The project uses the **Telco Customer Churn** dataset. It includes information about:
* **Demographics:** Gender, age range, and if they have partners/dependents.
* **Services:** Phone, multiple lines, internet, online security, streaming TV, etc.
* **Account Info:** Tenure, contract type, payment method, paperless billing, monthly charges, and total charges.

## 🛠️ Tech Stack & Libraries
* **Data Handling:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`, `Seaborn`
* **Machine Learning:** `Scikit-Learn`, `XGBoost`
* **Data Balancing:** `Imbalanced-Learn` (SMOTE)
* **Model Storage:** `Pickle`

## 🚀 Key Features
1.  **Exploratory Data Analysis (EDA):** Deep dive into correlations between contract types and churn rates.
2.  **Data Preprocessing:** Handling missing values in `TotalCharges`, encoding categorical variables, and feature scaling.
3.  **Handling Imbalance:** Using SMOTE to ensure the model doesn't ignore the minority "Churn" class.
4.  **Modeling:** Comparative analysis using Logistic Regression, Random Forest, and **XGBoost**.
5.  **Evaluation:** Metrics focused on **Recall** and **F1-Score** to minimize missed churners.

## 📂 Project Structure
```text
churn-prediction-ml/
├── data/                   # Raw and processed data
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── notebooks/              # Analysis and modeling
│   └── Customer_Churn_Prediction_using_ML.ipynb
├── requirements.txt        # Project dependencies
└── README.md               # You are here!
