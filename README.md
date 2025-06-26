
# 📊 Customer Churn Analysis & Prediction Dashboard

## 🔍 Project Overview
This project focuses on analyzing customer churn for a telecom company using a public dataset. I performed data cleaning, exploratory data analysis (EDA), feature engineering, built a machine learning model to predict churn, and created a visual dashboard for business insights.

## 🧠 Objective
- Identify key factors that influence customer churn
- Build a predictive model to classify churn risk
- Present actionable insights using visualizations and dashboard

---

## 📂 Dataset
- **Source**: [Telco Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Rows**: 7,043 customers  
- **Columns**: Customer demographics, account information, service details, churn status

---

## 🛠️ Tools & Technologies
- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Google Colab** for development
- **Power BI** for interactive dashboard
- **GitHub** for version control

---

## 🚀 Project Pipeline

1. **Data Cleaning**
   - Handled missing values in TotalCharges
   - Converted categorical features to numeric (Label/One-hot encoding)
   - Removed irrelevant columns like customerID

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution
   - Analyzed churn by contract type, tenure, and payment method
   - Built correlation heatmap to identify influential features

3. **Model Building**
   - Used Random Forest for binary classification
   - Achieved accuracy of `XX%` and recall of `YY%` (adjust based on your result)

4. **Feature Importance**
   - Identified top features influencing churn:
     - Contract Type
     - Tenure
     - Monthly Charges
     - Internet Service Type

5. **Dashboard Creation**
   - Built Power BI dashboard with filters and KPIs:
     - Churn Rate
     - Churn by Plan Type
     - Monthly Revenue at Risk

---

## 📊 Key Insights
- Customers with month-to-month contracts churn significantly more than those with yearly contracts.
- Senior citizens and customers with fiber-optic internet are more likely to churn.
- Long-tenure customers and those on auto-payment plans have lower churn.

---

## 💼 Business Recommendations
- Offer loyalty discounts to long-tenure customers
- Encourage customers to switch to yearly plans
- Introduce personalized retention offers for high-risk segments

---

## 📎 Files in this Repository
- `notebooks/churn_analysis.ipynb` – Python code
- `data/telco.csv` – Dataset
- `dashboard/churn_dashboard.pbix` – Power BI file
- `report/churn_summary.pdf` – Project summary
