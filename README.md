# Employee Attrition Prediction (HR Analytics)

## 📌 Project Overview
Employee attrition is a critical challenge for organizations worldwide. Understanding why employees leave and predicting attrition risk enables HR teams to take proactive measures to improve retention and workforce satisfaction.  

In this project, I conducted **Exploratory Data Analysis (EDA)** and built **Machine Learning models** using the IBM HR Analytics dataset to predict whether an employee is likely to leave the organization.  

---

## 🎯 Objectives
- Perform **EDA** to identify key patterns and trends in attrition.  
- Build and evaluate **classification models** to predict employee attrition.  
- Highlight the most important factors influencing attrition.  
- Provide **data-driven recommendations** to HR teams for employee retention.  

---

## 🗂 Dataset
- **Source:** [IBM HR Analytics Employee Attrition Dataset (Kaggle)](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)  
- **File Used:** `WA_Fn-UseC_-HR-Employee-Attrition.csv`  
- **Size:** 1470 rows × 35 features  

**Key Features:**  
- **Demographics:** Age, Gender, MaritalStatus, Education  
- **Job-related:** Department, JobRole, MonthlyIncome, Overtime, YearsAtCompany  
- **Satisfaction:** JobSatisfaction, EnvironmentSatisfaction, WorkLifeBalance  
- **Target Variable:** Attrition (Yes/No)  

---

## 🛠 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost  

---

## 🔎 Exploratory Data Analysis (EDA)
Some important insights from the data:  
- Employees working **OverTime** are more likely to leave.  
- **Younger employees (<30 years)** show higher attrition rates.  
- **Low job satisfaction** and **poor work-life balance** strongly correlate with attrition.  
- Higher **monthly income** is associated with lower attrition.  

**📊 Visualizations included:**  
- Attrition distribution  
- Attrition by Age, Department, and JobRole  
- Correlation heatmap  
- Monthly Income vs Attrition  

---

## 🤖 Models Implemented
### 1. Random Forest Classifier  
- **ROC-AUC:** ~0.85  
- Good interpretability with feature importance.  

### 2. XGBoost Classifier  
- **ROC-AUC:** ~0.87  
- Outperformed Random Forest with better precision-recall tradeoff.  

---

## 🏆 Key Business Insights
- **Overtime** is the strongest driver of attrition → organizations should reduce excessive workload.  
- **Improving job satisfaction and work-life balance** can significantly lower attrition.  
- **Salary benchmarking** is important as higher compensation correlates with retention.  
- **Young employees** need more engagement and career development opportunities.  

---

