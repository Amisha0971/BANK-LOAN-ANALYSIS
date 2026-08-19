# 🏦 Bank Loan Analysis – Capstone Project

This project focuses on analyzing a bank's lending activities to evaluate **loan performance, borrower behavior, and portfolio health** using **Excel, SQL, Power BI, and Python**.  
The analysis tracks key lending KPIs and presents insights through interactive dashboards to support data-driven lending decisions.

---

## 📌 Project Overview

The **Bank Loan Analysis** project is an end-to-end analytics solution that examines loan applications, funded amounts, repayments, and borrower characteristics.

The project covers:
- Loan portfolio performance
- Good Loans vs Bad Loans analysis
- Month-to-Date (MTD) and Month-over-Month (MoM) trends
- Regional, borrower, and loan purpose patterns

---

## 🎯 Business Objective

The objective of this project is to:
- Monitor total loan applications, funded amounts, and repayments
- Evaluate Good Loan vs Bad Loan performance
- Track MTD and MoM trends for key KPIs
- Analyze loans by state, purpose, term, employment length, and home ownership
- Assess overall portfolio quality and credit risk

---

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- **SQL (MySQL)**
- **Power BI Desktop**
- Power Query
- **Python (Jupyter Notebook)**

---

## 🔄 Project Workflow

- Reviewed loan domain and lending lifecycle concepts
- Cleaned and standardized raw loan data
- Performed SQL analysis for KPI calculations → [View SQL Queries](./Finance_loan.sql)
- Used Python for exploratory analysis and KPI validation → [View Python Notebook](./Bank%20Loan%20Analysis.ipynb)
- Built star-schema data model in Power BI
- Created DAX measures for KPIs, MTD, and MoM analysis
- Developed interactive dashboards with filters and drill-downs → [View Dashboards PDF](./BANK_LOAN_ANALYSIS_PROJECT%20DASHBOARD.pdf)

---

## 📊 Dashboards Created

### 1️⃣ Summary Dashboard

![Summary Dashboard](./Bank%20Loan%20Summary%20Dashboard.png)

**KPIs included:**
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income (DTI)
- Good Loan vs Bad Loan Percentage
- MTD and MoM comparisons

---

### 2️⃣ Overview Dashboard

![Overview Dashboard](./Bank%20Loan%20Overview%20Dashboard.png)

**Visual analysis includes:**
- Monthly trend by issue date
- State-wise funded and received amounts (map)
- Loan term distribution (36 vs 60 months)
- Employee length analysis
- Loan purpose breakdown
- Home ownership analysis

---

### 3️⃣ Details Dashboard

- Loan-level detailed table
- Borrower details, loan purpose, grade, funded amount, interest rate, and collections
- Used for detailed reporting and analysis

---

## 📈 Key Insights (From Dashboard)
- Majority of loans fall under **Good Loan** category (Fully Paid & Current)
- **Bad Loans (Charged Off)** show lower recovery amounts
- Certain states have higher loan demand and funding
- Borrowers with longer employment length demonstrate better repayment behavior
- Loan purpose and home ownership have a significant impact on loan performance

---

## 💡 Business Recommendation

The $28.2M recovery shortfall in bad loans, combined with higher average DTI (14.00%) among charged-off borrowers, suggests that implementing stricter DTI thresholds during loan approval could meaningfully reduce default exposure.

---

## 🧠 Skills Demonstrated

- Financial & Banking Data Analysis
- SQL Aggregations and KPI Calculations
- Python-based Data Validation
- Data Modeling (Star Schema)
- DAX Measures (MTD, MoM, KPIs)
- Power BI Dashboard Design

---

## 📁 Project Files

| File | Description |
|---|---|
| [Finance_loan.sql](./Finance_loan.sql) | All SQL queries for KPI calculations |
| [Bank Loan Analysis.ipynb](./Bank%20Loan%20Analysis.ipynb) | Python notebook for EDA and validation |
| [financial_loan.csv](./financial_loan.csv) | Raw dataset (38,576 loan records) |
| [BANK_LOAN_ANALYSIS_PROJECT.pbix](./BANK_LOAN_ANALYSIS_PROJECT.pbix) | Power BI source file |
| [BANK_LOAN_ANALYSIS_PROJECT DASHBOARD.pdf](./BANK_LOAN_ANALYSIS_PROJECT%20DASHBOARD.pdf) | All 3 dashboards in PDF |
| [Bank Loan Analysis project-DESKTOP-6T3AV6G.xlsx](./Bank%20Loan%20Analysis%20project-DESKTOP-6T3AV6G.xlsx) | Excel analysis file |
| [Bank_Loan_Analysis_Documentation.docx](./Bank_Loan_Analysis_Documentation.docx) | Full project documentation |

---

## ✅ Conclusion

This project demonstrates a complete **banking analytics workflow** using Excel, SQL, Python, and Power BI.  
It highlights the ability to monitor loan portfolios, evaluate credit risk, and present actionable insights through professional dashboards to support lending and risk-management decisions.

---

## 👩‍💻 Author

**Amisha Ninawe**  
Aspiring Data Analyst | SQL | Power BI | Python | Excel  
⭐ Feel free to star this repository if you find it useful!
