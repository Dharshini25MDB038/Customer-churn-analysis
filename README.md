# Telecom Customer Churn Analysis and Prediction

## 📌 Project Overview
In today’s highly competitive telecom industry, customer retention is critical for sustainable growth. Customer churn directly impacts revenue and profitability.  
This project focuses on performing an **end-to-end customer churn analysis and prediction** by integrating **SQL Server, Power BI, and Python-based Machine Learning** to generate actionable business insights and predict potential churners.

---

## 🎯 Project Objectives
- Analyze customer churn patterns across multiple dimensions
- Identify key factors influencing customer attrition
- Build an interactive Power BI dashboard for business users
- Develop a machine learning model to predict future churners
- Enable data-driven decision-making for churn reduction strategies

---

## 🛠️ Tools & Technologies
- **Database:** Microsoft SQL Server (SSMS)
- **Visualization:** Power BI
- **Programming Language:** Python
- **Machine Learning:** Random Forest Classifier (Scikit-learn)
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **IDE & Tools:** Jupyter Notebook, Anaconda

---

## 🧩 Project Workflow

### STEP 1 – ETL Process in SQL Server
- Imported raw customer data into a **staging table**
- Performed data validation and null analysis
- Cleaned and transformed data into a **production table**
- Created SQL **views** for analysis and ML usage:
  - `vw_ChurnData`
  - `vw_JoinData`

---

### STEP 2 – Data Transformation in Power BI
- Created calculated columns such as:
  - Churn Status
  - Monthly Charge Range
- Built mapping tables for:
  - Age Groups
  - Tenure Groups
- Unpivoted service-related columns for service-level analysis

---

### STEP 3 – Power BI Measures
- Total Customers
- New Joiners
- Total Churn
- Churn Rate

---

### STEP 4 – Power BI Dashboard
Developed an interactive dashboard covering:
- Customer demographics
- Account & payment details
- Geographic churn distribution
- Service usage patterns
- Churn categories and reasons (with tooltips)

---

### STEP 5 – Customer Churn Prediction (Machine Learning)
- Exported SQL views into Excel for ML processing
- Preprocessed data using label encoding
- Built and trained a **Random Forest Classifier**
- Evaluated model using:
  - Confusion Matrix
  - Classification Report
- Identified key churn-driving features using feature importance
- Predicted churn for newly joined customers

---

### STEP 6 – Visualization of Predicted Churn
- Imported prediction results into Power BI
- Created a dedicated **Churn Prediction Dashboard**
- Visualized predicted churners by:
  - Demographics
  - Account details
  - Geography
  - Revenue metrics

---

## 📊 Key Metrics
- Total Customers
- New Joiners
- Total Churn
- Churn Rate
- Predicted Churn Count

---

## 🚀 Key Outcomes
- Identified critical churn drivers such as contract type, tenure, and service usage
- Built a scalable churn prediction model
- Delivered an end-to-end analytics solution combining BI and ML
- Enabled proactive churn management strategies

---

## 📌 Conclusion
This project demonstrates a complete **data analytics and machine learning pipeline**, showcasing strong skills in **SQL, Power BI, and Python**. It reflects real-world telecom churn analysis and can be adapted to other industries such as retail, finance, and healthcare.

---

## 👤 Author
**Dharshini R**  
Data Analytics / Data Science Enthusiast


