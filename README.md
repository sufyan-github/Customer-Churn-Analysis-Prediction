# Telco Customer Churn Prediction  

## 📌 Project Overview  
This project analyzes the **Telco Customer Churn dataset** to predict whether a customer will leave (churn) or stay with the company. Customer churn prediction is crucial for telecommunication companies to retain customers, reduce revenue loss, and improve service quality.  

The dataset contains customer demographics, account information, and service usage patterns. By applying **data preprocessing, exploratory data analysis (EDA), and machine learning models**, we aim to build an effective churn prediction system.  

---

## 📂 Dataset Information  
- **File Name:** Telco-Customer-Churn.csv  
- **Total Records:** 7,043  
- **Total Features:** 21  

### Columns Description
1. **customerID** – Unique customer identifier  
2. **gender** – Male/Female  
3. **SeniorCitizen** – 0 = No, 1 = Yes  
4. **Partner** – Yes/No  
5. **Dependents** – Yes/No  
6. **tenure** – Months with the company  
7. **PhoneService** – Yes/No  
8. **MultipleLines** – No, Yes, No phone service  
9. **InternetService** – DSL, Fiber optic, No  
10. **OnlineSecurity** – Yes/No/No internet service  
11. **OnlineBackup** – Yes/No/No internet service  
12. **DeviceProtection** – Yes/No/No internet service  
13. **TechSupport** – Yes/No/No internet service  
14. **StreamingTV** – Yes/No/No internet service  
15. **StreamingMovies** – Yes/No/No internet service  
16. **Contract** – Month-to-month, One year, Two year  
17. **PaperlessBilling** – Yes/No  
18. **PaymentMethod** – Electronic check, Mailed check, Bank transfer, Credit card  
19. **MonthlyCharges** – Customer’s monthly fee  
20. **TotalCharges** – Total amount billed (needs numeric conversion)  
21. **Churn** – Target variable (Yes/No)  

---

## 🛠️ Preprocessing Steps  
- Convert `TotalCharges` from string → numeric  
- Handle missing/invalid values  
- Encode categorical variables (e.g., gender, contract type)  
- Normalize/scale numerical features (`MonthlyCharges`, `TotalCharges`, `tenure`)  

---

## 📊 Exploratory Data Analysis (EDA)  
- **Churn distribution** (percentage of customers who left)  
- **Demographics vs Churn** (e.g., gender, senior citizens)  
- **Service usage vs Churn** (Internet, Phone, Streaming)  
- **Contract type vs Churn**  
- **Correlation analysis** (tenure, charges, churn)  

---

## 🤖 Machine Learning Models (Planned)  
- Logistic Regression  
- Random Forest  
- XGBoost  
- Neural Networks  

### Evaluation Metrics  
- Accuracy  
- Precision, Recall, F1-score  
- ROC-AUC  
- Confusion Matrix  

---

## 📌 Objectives  
- Identify key factors influencing customer churn  
- Build predictive models to classify churners vs non-churners  
- Provide actionable insights for retention strategies  

---

## 🚀 How to Run  
1. Clone the repository  
   ```bash
   git clone https://github.com/github-sufyan/Customer-Churn-Analysis-Prediction.git
   cd Customer-Churn-Analysis-Prediction
