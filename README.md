# 🏥 Healthcare Cost Optimization Project

## 📌 Overview
This project analyzes **healthcare claims data** to detect inefficiencies in patient billing, identify revenue leakage due to claim denials, and forecast operational costs using **SQL, Power BI, and Predictive Analytics**. 

### ✅ **Key Objectives**
- **Analyze** hospital claims to detect **unnecessary expenditures**.
- **Identify** revenue loss from **claim denials and inefficiencies**.
- **Forecast future costs** using **Time Series Modeling**.
- **Build a Power BI Dashboard** for actionable insights.

---

## 📂 **Project Structure**
```
📂 Healthcare-Cost-Optimization
🎪 Power BI Dashboard
   │-- healthcare_claims_cleaned_final.csv
   │-- healthcare_claims_aggregated_final.csv
📝 SQL Data Cleaning
   │-- healthcare_claims.sql
📊 Predictive Analytics
   │-- predict.ipynb
📋 requirements.txt
📚 README.md
```

---

## 📈 **1. Power BI Dashboard**
### **Dashboard Features**
- ✅ **Total Claims Processed**
- ✅ **Claim Denial Rate (%)**
- ✅ **Revenue Loss due to Denied Claims**
- ✅ **Top Diagnoses by Cost**
- ✅ **High-Cost Hospitals (Heatmap)**
- ✅ **Trend Analysis of Claims Over Time**

### **🔗 How to Use**
1. Open `healthcare_claims_cleaned_final.csv` & `healthcare_claims_aggregated_final.csv` in **Power BI**.
2. Load data and apply **One-to-Many Relationships** using a Date Table.
3. Use **Power BI visuals** (Line Chart, Pie Chart, Heatmap) for insights.

---

## 🛋 **2. SQL Data Cleaning & Transformation**
### **📌 Key SQL Queries**
- **Removing Duplicate Claims**
- **Handling Missing Values**
- **Aggregating Total Claims per Hospital**
- **Calculating Claim Denial Rate**

### **🛠 How to Run SQL Queries**
1. Open `healthcare_claims.csv` in **SQL Server / MySQL / PostgreSQL**.
2. Run **SQL queries** from the file `healthcare_claims.sql`.
3. Export the cleaned data (`healthcare_claims_cleaned_final.csv`).

---

## 📊 **3. Predictive Analytics - Forecasting Future Costs**
### **📌 Model Used**
- **Time Series Forecasting (ARIMA)**
- **Python Libraries: pandas, statsmodels, matplotlib**

### **🔧 How to Run Prediction Model**
1. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
2. Open **Jupyter Notebook**:
   ```sh
   jupyter notebook predict.ipynb
   ```
3. Run all cells to forecast **future operational costs**.

---

## ⚙️ **4. Installation & Setup**
### **🔧 Requirements**
- **Python 3.8+**
- **Power BI**
- **SQL Database (PostgreSQL/MySQL)**
- **Jupyter Notebook**

### **📞 Install Required Libraries**
```sh
pip install -r requirements.txt
```

---

## 📀 **5. Dataset**
| Column Name         | Description                              |
|---------------------|------------------------------------------|
| `Claim_ID`         | Unique identifier for each claim         |
| `Patient_Age`      | Age of the patient                       |
| `Diagnosis`        | Medical condition diagnosed             |
| `Treatment_Cost`   | Cost of treatment provided              |
| `Insurance_Coverage` | Percentage of cost covered by insurance |
| `Claim_Status`     | Approved / Denied claim status          |
| `Hospital_ID`      | Unique ID for hospitals                 |
| `Billing_Amount`   | Total billed amount                     |
| `Date`            | Claim filing date                        |

---

## 🚀 **6. Future Enhancements**
- ✅ Integrate **Machine Learning Models** for fraud detection.
- ✅ Automate **real-time analytics** using **Power BI Service**.
- ✅ Use **Cloud SQL Database** for scalability.

---

🚀 **Let's optimize healthcare costs using data-driven insights!**
