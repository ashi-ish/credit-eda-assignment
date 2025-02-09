# 📊 Exploratory Data Analysis (EDA) in Risk Analytics  

## 📝 Project Overview  

This project focuses on **Exploratory Data Analysis (EDA) in risk analytics for banking and financial services**. The objective is to analyze **loan applicants' data** and identify factors that influence **loan default risks**. Using **EDA techniques**, we explore patterns, detect outliers, handle missing values, and derive insights that help financial institutions make informed lending decisions.  

## 🎯 Business Problem  

Lending companies face challenges in approving loans due to **insufficient credit history** of applicants. This can result in:  
- **Loss of business** if eligible applicants are rejected.  
- **Financial loss** if high-risk applicants default on loans.  

The goal of this analysis is to:  
✔ **Identify key factors affecting loan default**  
✔ **Develop risk-based lending strategies** (e.g., higher interest rates for risky applicants)  
✔ **Ensure fair loan approvals for creditworthy applicants**  

## 📂 Dataset Details  

The dataset consists of **three files**:  

1️⃣ **`application_data.csv`** – Contains applicant details at the time of loan application.  
2️⃣ **`previous_application.csv`** – Historical loan application records for each client.  
3️⃣ **`columns_description.csv`** – Data dictionary explaining all variables.  

## 🔍 Key Analysis Steps  

### 1️⃣ Data Cleaning & Preprocessing  
✅ Handle **missing values** by appropriate imputation/removal strategies  
✅ Identify **outliers** and assess their impact on analysis  
✅ Check for **data imbalance** in loan approval and default categories  

### 2️⃣ Univariate & Bivariate Analysis  
✅ Explore **distributions of numerical & categorical variables**  
✅ Perform **segmented analysis** for applicants with/without payment difficulties  
✅ Compare loan approval patterns based on income, credit history, etc.  

### 3️⃣ Correlation Analysis  
✅ Identify **top 10 correlated variables** impacting loan default risk  
✅ Segment data based on **loan defaulters vs. non-defaulters**  

### 4️⃣ Data Visualization  
✅ Use **histograms, box plots, heatmaps, and bar charts** for insights  
✅ Compare approval rates, loan amounts, and repayment behavior  

## 📌 Results & Business Insights  

- High **income-to-loan ratio** applicants have **lower default risk**  
- Applicants with **previously rejected loans** are **more likely to default**  
- Higher **loan amounts & longer tenure** increase **default probability**  
- **Data imbalance** is observed between defaulters & non-defaulters  

## 🛠 Technologies Used  

- **Programming**: Python (Pandas, NumPy, Matplotlib, Seaborn)  
- **EDA & Analysis**: Jupyter Notebook, Tableau (for visualizations)  

## 📁 Files Included  

📜 `EDA_Loan_Default.ipynb` → Jupyter Notebook with **code & insights**  
📂 `datasets/` → Contains raw loan application datasets  
