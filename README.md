# 📊 Bank Loan Performance Analysis & Risk Dashboard

## 🧭 Overview

This project delivers a comprehensive analysis of bank loan data to evaluate lending performance, borrower risk, and financial trends. By integrating **SQL, Python, and Power BI**, the solution provides an end-to-end analytical workflow—from data processing to interactive visualization.

The dashboard enables stakeholders to monitor loan portfolio health, identify risk segments, and make data-driven lending decisions.

---

## 🎯 Business Problem

Financial institutions require a centralized system to:

* Track loan application trends and funding distribution
* Monitor repayment performance and cash flow
* Identify high-risk (default-prone) borrowers
* Evaluate lending efficiency across regions and customer segments

This project addresses these needs by building a scalable analytics solution with real-time insights.

📄 Full Problem Statement: Included in repository

---

## 🏗️ Solution Architecture

**Data Flow:**

```
Raw Data → Data Cleaning (Python) → SQL Analysis → Power BI Dashboard
```

* **Python (Pandas):** Data cleaning, preprocessing
* **SQL:** KPI calculations, aggregations
* **Power BI:** Data modeling & dashboard creation

---

## 🛠️ Tech Stack

| Layer           | Tools Used             |
| --------------- | ---------------------- |
| Data Processing | Python (Pandas, NumPy) |
| Querying        | SQL                    |
| Visualization   | Power BI               |
| Data Source     | Excel Dataset          |

---

## 📊 Dashboard Preview

### 🔹 Summary Dashboard

![Summary Dashboard](images/Summary.png)

### 🔹 Overview Dashboard

![Overview Dashboard](images/Overview.png)

### 🔹 Detailed Dashboard

![Details Dashboard](images/Details.png)

---

## 📈 Key Metrics

| KPI                     | Value  |
| ----------------------- | ------ |
| Total Loan Applications | 38.6K  |
| Total Funded Amount     | $436M  |
| Total Amount Received   | $473M  |
| Average Interest Rate   | 12.05% |
| Average DTI             | 13.33% |

---

## ⚖️ Loan Portfolio Quality

| Category   | Applications | Funded Amount | Amount Received |
| ---------- | ------------ | ------------- | --------------- |
| Good Loans | 33K          | $370.2M       | $435.8M         |
| Bad Loans  | 5K           | $65.5M        | $37.3M          |

📌 **Insight:** ~86% of loans are classified as good loans, indicating a relatively healthy portfolio.

---

## 📊 Analytical Insights

* 📈 Loan applications show consistent growth over time
* 🏠 Mortgage holders account for the highest loan funding
* 👨‍💼 Borrowers with longer employment tenure receive higher loan amounts
* ⚠️ Bad loans represent a smaller portion but significantly impact recovery
* 🌍 Regional variations highlight high-performing and high-risk states

---

## 📌 Features

* Interactive dashboards with slicers (State, Purpose, Grade)
* Month-to-Date (MTD) and Month-over-Month (MoM) tracking
* Loan segmentation (Good vs Bad loans)
* Multi-level drill-down analysis
* Clean and intuitive UI for business users

---

## 📂 Repository Structure

```
Bank-Loan-Analysis/
│
├── data/                # Raw dataset
├── sql/                 # SQL queries
├── notebook/            # Python analysis
├── powerbi/             # Dashboard file (.pbix)
├── images/              # Dashboard screenshots
├── report/              # Project documentation
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository
2. Open the Power BI (.pbix) file
3. Load dataset (if required)
4. Explore dashboards interactively

---

## 💼 Business Impact

This solution enables:

* Improved loan approval strategies
* Better risk management through segmentation
* Data-driven decision-making for financial planning
* Identification of high-value customer segments

---

## 🔮 Future Enhancements

* 🔹 Predictive modeling (Loan Default Prediction using ML)
* 🔹 Real-time data integration
* 🔹 Deployment via Power BI Service / Cloud
* 🔹 Automated ETL pipeline

---

## 👤 Author

**Rishabh Tomar**
Aspiring Data Analyst | SQL | Python | Power BI

---
