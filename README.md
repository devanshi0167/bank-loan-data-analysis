# bank-loan-data-analysis
An end-to-end data analytics and credit risk pipeline engineered to evaluate loan portfolio health, quantify risk exposure, and drive institutional profitability. This project processes raw financial records to uncover critical trends in borrower behavior, model default probabilities, and deliver data-driven strategic insights for risk mitigation.


# 🏦💰 Bank Loan Analysis — Data Analytics Project 📊📈

## 🚀 Project Overview

This is an end-to-end **Bank Loan Data Analysis Project** designed to evaluate loan portfolio performance, borrower behavior, portfolio risk, and profitability.

The project uses **Python, Pandas, NumPy, Matplotlib, and Seaborn** for data cleaning, KPI creation, exploratory data analysis, and visualization.

The final goal is to help a bank understand its loan performance, identify risky borrower segments, reduce losses, and improve lending strategy using data-driven insights.

---

## 📚🧭 Table of Contents

- [📌 Business Problem](#-business-problem)
- [🎯 Project Objectives](#-project-objectives)
- [📊 Results Snapshot](#-results-snapshot)
- [🔗 Quick Links](#-quick-links)
- [🛠️ Tools & Technologies Used](#️-tools--technologies-used)
- [📂 Dataset Description](#-dataset-description)
- [📈 KPI Requirements](#-kpi-requirements)
- [✅ Good Loan vs Bad Loan Analysis](#-good-loan-vs-bad-loan-analysis)
- [📉 Visualization Requirements & Chart Insights](#-visualization-requirements--chart-insights)
- [🧠 Key Insights Summary](#-key-insights-summary)
- [🏦 Business Recommendations](#-business-recommendations)
- [🧾 Final Conclusion](#-final-conclusion)
- [📁 Project Structure](#-project-structure)
- [👩‍💻 Author](#-author)

---

## 📌 Business Problem

Banks receive thousands of loan applications from different states, income groups, employment backgrounds, and loan purposes. However, without proper analysis, it becomes difficult to clearly understand:

- 👥 Borrower repayment behavior
- 💸 Loan profitability and losses
- 📅 Seasonal trends in loan demand
- ⚠️ High-risk and low-risk customer groups
- 📊 Operational lending KPIs
- 🌍 Portfolio risk concentration

This project solves these challenges by analyzing loan data across multiple KPIs, borrower segments, loan types, and repayment patterns.

The main goal is to support better underwriting decisions, reduce charge-offs, improve profitability, and build a more data-driven lending strategy.

---

## 🎯 Project Objectives

The major objectives of this project are:

- ✅ Calculate core lending KPIs
- ✅ Compare Good Loans and Bad Loans
- ✅ Identify high-risk and profitable borrower segments
- ✅ Analyze loan trends by month, state, term, employment length, purpose, and home ownership
- ✅ Understand repayment behavior and portfolio performance
- ✅ Provide business recommendations to reduce losses and improve ROI

---

## 📊 Results Snapshot

| 📌 Metric | 📈 Result |
|---|---:|
| 💰 Portfolio Net Profit | $37.31 Million |
| 📉 Total Loss from Bad Loans | $28.25 Million |
| ✅ Good Loan Success Rate | 86.18% |
| 🌍 Highest Performing State | California |
| 🏆 Low-Risk Groups | Mortgage Holders and 10+ Year Employees |
| ⚠️ High-Risk Groups | Renters and Employees with <1 Year Experience |

---

## 🔗 Quick Links

- 📄 Project Report: `Bank Loan Analysis Report.pdf`
- 🧩 Business Problem Document: `Business Problem`
- 📘 Jupyter Notebook: `Bank Loan Analysis.ipynb`
- 📂 Dataset: `Bank_loan_data.csv`
- 🖼️ Visualizations: `images/`
- 📊 GitHub Repository: `Bank-Loan-Analysis-Python`

---

## 🛠️ Tools & Technologies Used

| 🧰 Tool / Technology | 🎯 Purpose |
|---|---|
| 🐍 Python | Data analysis and visualization |
| 🐼 Pandas | Data cleaning, preprocessing, and aggregation |
| 🔢 NumPy | Numerical operations |
| 📊 Matplotlib | KPI charts and visualizations |
| 📈 Seaborn | Exploratory data analysis charts |
| 📓 Jupyter Notebook | Analysis and reporting |
| 📄 CSV / Excel | Dataset source |

---

## 📂 Dataset Description

The dataset contains borrower demographics, financial details, loan attributes, repayment status, and other lending-related information.

### 🧹 Preprocessing Steps Performed

- 🧼 Removed missing and invalid values
- 🗂️ Standardized date, category, and percentage formats
- 🔢 Converted DTI, income, term, and interest rate into numeric formats
- 📅 Derived month and year columns for time-based analysis
- 🏷️ Categorized loans into:
  - ✅ Good Loans
  - ❌ Bad Loans
- 🚫 Filtered incomplete or irrelevant records
- 📊 Prepared aggregated datasets for KPI and visualization analysis

---

## 📈 KPI Requirements

| 📌 KPI | 📊 Value |
|---|---:|
| 📝 Total Loan Applications | 38,576 |
| 💵 Total Funded Amount | $435.76 Million |
| 💰 Total Amount Received | $473.07 Million |
| 📈 Net Portfolio Return | $37.31 Million |
| 🏦 Average Interest Rate | 12.05% |
| 📉 Average DTI | 13.33% |

### 🔍 KPI Insights

- 📌 The bank received strong loan demand with more than 38,000 applications.
- 💰 Total repayment amount is higher than the total funded amount, showing a profitable portfolio.
- 🏦 The average interest rate of 12.05% indicates moderate lending risk.
- 📉 The average DTI of 13.33% suggests that many borrowers have manageable debt levels.

---

## ✅ Good Loan vs Bad Loan Analysis

## ✅ Good Loans

Good loans are loans where the borrower successfully repaid the loan.

| 📌 Metric | 📊 Value |
|---|---:|
| 📝 Applications | 33,243 |
| 💵 Funded Amount | $370.22 Million |
| 💰 Amount Received | $435.79 Million |
| 📊 Share of Total Loans | 86.18% |
| 📈 Profit | $65.56 Million |

### 💡 Insight

Good Loans form the strong and profitable foundation of the bank’s loan portfolio. These loans are mainly concentrated among stable borrower groups such as mortgage holders and long-term employees.

---

## ❌ Bad Loans

Bad loans are loans that were charged off and resulted in financial loss.

| 📌 Metric | 📊 Value |
|---|---:|
| 📝 Applications | 5,333 |
| 💵 Funded Amount | $65.53 Million |
| 💰 Amount Received | $37.28 Million |
| 📊 Share of Total Loans | 13.82% |
| 📉 Loss | $28.25 Million |

### ⚠️ Insight

Bad Loans are the major source of portfolio losses. These loans require tighter underwriting, better borrower assessment, and improved collection strategies.

---

## 📉 Visualization Requirements & Chart Insights

### 1️⃣ Total Funded Amount by Month 📅💵

**Insight:** Funding remains stable throughout the year, with a strong rise in December. This indicates peak loan demand during the year-end period.

---

### 2️⃣ Total Amount Received by Month 📅💰

**Insight:** Repayments follow a similar monthly pattern, with the highest collection observed in December.

---

### 3️⃣ Total Loan Applications by Month 📝📅

**Insight:** Loan applications remain consistent across months, with a noticeable increase toward the end of the year.

---

### 4️⃣ Total Funded Amount by State 🌍💵

**Insight:** California receives the highest loan funding, making it the most important state in the portfolio but also creating regional concentration risk.

---

### 5️⃣ Total Amount Received by State 🌍💰

**Insight:** California also generates the highest repayment amount, confirming strong performance but also high dependency on one state.

---

### 6️⃣ Total Funded Amount by Term ⏳💵

**Insight:** 36-month loans are the most preferred and most funded loan term.

---

### 7️⃣ Total Amount Received by Term ⏳💰

**Insight:** Shorter-term loans generate higher repayments and show better repayment efficiency.

---

### 8️⃣ Total Funded Amount by Employee Length 👔💵

**Insight:** Borrowers with 10+ years of employment receive the highest funding. Borrowers with less than 1 year of employment are comparatively riskier.

---

### 9️⃣ Total Amount Received by Employee Length 👔💰

**Insight:** Long-term employees generate reliable and higher repayments, making them a safer borrower group.

---

### 🔟 Total Funded Amount by Loan Purpose 🎯💵

**Insight:** Debt Consolidation loans dominate the funded amount. This creates product concentration risk.

---

### 1️⃣1️⃣ Total Amount Received by Loan Purpose 🎯💰

**Insight:** Debt Consolidation also contributes the highest repayment amount, making it both a profitable and risky loan category due to over-dependency.

---

### 1️⃣2️⃣ Total Funded Amount by Home Ownership 🏠💵

**Insight:** Mortgage holders receive the highest funding, showing that they are a preferred borrower group.

---

### 1️⃣3️⃣ Total Amount Received by Home Ownership 🏠💰

**Insight:** Mortgage owners generate the highest repayment amount, making them one of the most reliable borrower segments.

---

## 🧠 Key Insights Summary

- 💰 The overall loan portfolio is profitable with a net return of $37.31 Million.
- ✅ 86.18% of loans are Good Loans, showing strong portfolio quality.
- ❌ Bad Loans create a loss of $28.25 Million and need serious risk control.
- 🌍 California is the top-performing state but also creates regional dependency.
- 🎯 Debt Consolidation is the dominant loan purpose, creating product concentration risk.
- ⏳ 36-month loans show strong repayment efficiency.
- 🏠 Mortgage holders and 10+ year employees are the most reliable borrower groups.
- ⚠️ Renters and employees with less than 1 year of employment are higher-risk groups.
- 📅 December is the peak month for applications, funding, and repayments.

---

## 🏦 Business Recommendations

## 1️⃣ Improve Risk Control ⚠️🛡️

- Apply stricter underwriting for renters and new employees.
- Use risk-based pricing for high-risk borrower groups.
- Strengthen DTI and income verification.
- Closely monitor borrowers with unstable employment history.

---

## 2️⃣ Reduce Concentration Risk 🌍📉

- Expand lending operations beyond California.
- Focus on other strong markets such as Texas, New York, and Florida.
- Reduce over-dependency on Debt Consolidation loans.
- Diversify loan products and borrower categories.

---

## 3️⃣ Strengthen Collections 💰📞

- Improve early-stage collection reminders.
- Monitor risky borrowers before they become charge-offs.
- Increase recovery efforts for high-risk borrower segments.
- Use repayment behavior data to identify early warning signals.

---

## 4️⃣ Optimize Lending Profitability 📈🏦

- Focus more on long-term employees and mortgage holders.
- Promote 36-month loans due to strong repayment efficiency.
- Improve borrower screening before loan approval.
- Balance profit growth with risk control.

---

## 🧾 Final Conclusion

This analysis shows that the bank’s loan portfolio is profitable, but it also has important risk areas that need attention.

The bank earned a net portfolio return of **$37.31 Million**, even after facing **$28.25 Million** in losses from Bad Loans. This indicates that the overall lending business is performing well, but there is still room to reduce losses and improve portfolio stability.

### 🔑 Key Takeaways

- 💰 The portfolio is profitable and has strong repayment performance.
- ✅ Good Loans make up 86.18% of total loans.
- ❌ Bad Loans are responsible for major financial losses.
- 🌍 California and Debt Consolidation loans create concentration risk.
- 🏠 Mortgage holders and long-term employees are safer borrower groups.
- ⚠️ Renters and short-term employees require stricter risk evaluation.

### 🎯 Recommended Strategy

To improve future performance, the bank should:

- Tighten underwriting for Debt Consolidation loans.
- Apply risk-based pricing for renters and short-term employees.
- Diversify lending across more states.
- Focus on low-risk borrower groups.
- Improve collection and early-warning systems.

### ✅ Final Outcome

By improving risk control, reducing portfolio concentration, and focusing on reliable borrower groups, the bank can increase profitability, reduce default losses, and build a stronger data-driven lending strategy.

---

## 📁 Project Structure

```text
Bank-Loan-Analysis/
│
├── 📓 Bank Loan Analysis.ipynb
├── 📂 Bank_loan_data.csv
├── 🧩 Business Problem
├── 📄 Bank Loan Analysis Report.pdf
│
├── 🖼️ images/
│   ├── 01_Total_Funded_Amount_by_Month.png
│   ├── 02_Total_Received_Amount_by_Month.png
│   ├── 03_Total_Loan_Applications_by_Month.png
│   ├── 04_Total_Funded_Amount_by_State.png
│   ├── 05_Total_Amount_Received_by_State.png
│   ├── 06_Total_Funded_Amount_by_Term.png
│   ├── 07_Total_Amount_Received_by_Term.png
│   ├── 08_Total_Funded_Amount_by_Employee_Length.png
│   ├── 09_Total_Amount_Received_by_Employee_Length.png
│   ├── 10_Total_Funded_Amount_by_Loan_Purpose.png
│   ├── 11_Total_Amount_Received_by_Loan_Purpose.png
│   ├── 12_Total_Funded_Amount_by_Home_Ownership.png
│   └── 13_Total_Amount_Received_by_Home_Ownership.png
│
└── 📝 README.md
```

---

## 👩‍💻 Author

**Devanshi Sharma**  
🎓 B.Tech CSE AIML Student  
📊 Data Analytics Enthusiast  
🐍 Python | SQL | Power BI | Data Visualization  

---

## ⭐ Project Purpose

This project was created to demonstrate practical skills in:

- 🧹 Data cleaning
- 📊 KPI analysis
- 🔍 Exploratory data analysis
- 🧠 Business problem solving
- 📈 Data visualization
- 🏦 Banking and credit risk analytics
- 📝 Business recommendation writing

---

## 🌟 Final Note

This project represents a complete data analytics workflow, starting from raw loan data and ending with business insights, risk analysis, and strategic recommendations.
