# 📊 Customer Churn Prediction – Telco Dataset (Python, ML Project)

This project focuses on predicting customer churn for a telecom company using machine learning techniques. By analyzing customer behavior and contract features, we aim to identify patterns that indicate potential churn and help businesses retain customers proactively.

---

## 📌 Problem Statement

Customer churn is a critical issue for telecom companies, as acquiring new customers is costlier than retaining existing ones. The goal of this project is to build a classification model that can predict whether a customer is likely to churn, enabling the business to take timely retention actions.

---

## 📂 Dataset

- **Source:** Telco Customer Churn Dataset
- **Format:** CSV
- **Target Variable:** `Churn` (Yes/No)
- **Size:** ~7,000 records, 20+ features

---

## 🔧 Technologies Used

- **Python**  
- **Pandas, NumPy** – data manipulation  
- **Matplotlib, Seaborn** – data visualization  
- **Scikit-learn** – modeling & evaluation  
- **Jupyter Notebook**

---

## 📈 Workflow

1. **Data Loading & Exploration**  
   - Handled missing values and cleaned categorical columns
   - Explored correlations and class distribution

2. **Data Preprocessing**
   - Label encoding for binary columns
   - One-hot encoding for categorical features
   - Feature scaling (StandardScaler)

3. **Model Building**
   - Applied Logistic Regression, Random Forest
   - Evaluated using accuracy, confusion matrix, classification report

4. **Hyperparameter Tuning**
   - Used GridSearchCV for logistic regression optimization

5. **Model Interpretation**
   - Feature importance for Random Forest
   - Insights into top churn-driving variables

---

## 🔍 Key Results

- **Best Model:** Logistic Regression (after tuning)
- **Accuracy:** ~85% (can vary based on random state and train-test split)
- **Top Features Affecting Churn:**
  - Contract type
  - Monthly charges
  - Tenure

---

## 📊 Visualizations

- Distribution plots of churned vs non-churned
- Heatmap of correlations
- Bar charts for categorical churn trends

---

## ✅ Future Improvements

- Add ensemble models (XGBoost, LightGBM)
- Model explainability using SHAP
- Deploy model via Flask API or Streamlit dashboard

---

## 📁 Files

- `Telco_Customer_Churn_Python_Project1.ipynb` – Main analysis and model code
- `churn_data.csv` – Dataset (optional, if included)

---

## ✍️ Author

**Sunkara Venkataramana**  
- 📧 Vramana086@gmail.com  
- 🔗 [LinkedIn](https://linkedin.com/in/svramana1)  
- 💻 [GitHub](https://github.com/VENKATARAMANA810)

---
