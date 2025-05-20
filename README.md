# 📊 Synovus Financial Corp Bank Loan Report – Data Analysis Dashboard

## 🏦 Company Overview

**Synovus Financial Corp** is a prominent financial services company in the southeastern United States. The bank specializes in commercial and retail banking, investment services, and consumer loans. With a focus on customer-centric service and risk-optimized lending, Synovus is constantly enhancing its data-driven decision-making processes.

---

## 🎯 Business Objective

Synovus sought to:
- Identify patterns in loan application behavior and customer creditworthiness.
- Detect early indicators of loan default to reduce financial risk.
- Optimize interest rate assignment based on borrower risk profiles.
- Recommend data-backed improvements in product design and approval criteria.

---

## 🌐 Interactive Tableau Dashboard

🔗 **[View the Full Tableau Dashboard](https://public.tableau.com/app/profile/rishabh.parakh1925/viz/SynovusFinancialCorpDataAnalysis/Overview)**

---

## 📄 Field Definitions

📘 **[Click here for the TERMINOLOGIES USED.txt](TERMINOLOGIES%20USED.txt)** – Contains detailed definitions for each field in the loan dataset including `Loan ID`, `Grade`, `Interest Rate`, `Purpose`, and `DTI (Debt-to-Income Ratio)`.

---

## 📊 Dashboard Snapshots

### ✅ Overview Dashboard  
Provides high-level loan metrics and segmentation across employment length, state, and term.  
![Overview](Images/Synovus_Financial_Corp_Bank_Loan_Report_Overview.png)

---

### 📌 Details Dashboard  
Gives loan-level data on risk flags, purpose, term, and borrower characteristics for micro-level analysis.  
![Details](Images/Synovus_Financial_Corp_Bank_Loan_Report_Details.png)

---

### 🔄 Summary Dashboard  
Compares good vs bad loans, net recovery, and distribution across key metrics like interest rate and DTI.  
![Summary](Images/Synovus_Financial_Corp_Bank_Loan_Report_Summary.png)

---

## 📈 Key KPIs Explained

| **KPI**                          | **What It Means**                                                                 |
|----------------------------------|------------------------------------------------------------------------------------|
| **Total Loan Applications**      | Number of unique loan records analyzed – represents total demand. (38.6K loans)    |
| **Total Funded Amount**          | Total principal amount disbursed by Synovus. (₹435.8M)                             |
| **Total Received Amount**        | Total money repaid by borrowers. (₹473.1M)                                         |
| **Average Interest Rate**        | Mean interest rate across all loans – higher rates often signal higher risk. (12.05%) |
| **Average DTI Ratio**            | Debt-to-income ratio indicating how burdened borrowers are. (13.33%)              |
| **Good Loan Percentage**         | Loans that are current or fully paid. (86.2%)                                      |
| **Bad Loan Percentage**          | Loans that were charged off or defaulted. (13.8%)                                  |

---

## 🔍 Insights with Explanation

### 1. 📆 Loan Term Preference
- **73.2% of borrowers** opted for **60-month terms**, favoring smaller EMIs over shorter tenure.
- Longer durations, while attractive to borrowers, increase Synovus’ risk exposure and reduce liquidity turnaround.

### 2. 🧾 Loan Purpose Behavior
- **Debt consolidation** accounted for nearly **50%** of loan applications.
- This suggests a high segment of borrowers aim to restructure existing liabilities — which can be stable if income is verified.

### 3. 👨‍💼 Employment Tenure & Risk
- Majority of applicants with **10+ years of work experience** showed significantly **lower default rates**.
- Employment stability can serve as a strong predictor of repayment reliability.

### 4. 📊 Interest Rate vs Risk
- **Charged-off loans** had an **average interest rate of 13.88%**, compared to **11.64%** for fully paid loans.
- Higher interest correlates with riskier borrower profiles — signaling a potential opportunity to revise pricing models.

### 5. 📈 DTI Ratio Disparity
- Borrowers who defaulted had a **14% average DTI**, while those who fully paid averaged **13%**.
- Small differences in DTI can significantly impact repayment capacity, especially under economic stress.

### 6. 🏡 Home Ownership vs Default
- **Homeowners** (vs renters) were slightly more consistent in repayments, possibly due to stronger financial stability or asset backing.
- Homeownership can be used as a secondary verification indicator during loan approval.

### 7. 🗺️ Geographic Hotspots
- States with high application volumes also had **concentrated defaults**.
- Geographical targeting could help refine marketing strategies and regional risk thresholds.

---

## ✅ Recommendations

1. **Risk-Based Verification:**
   - Strengthen KYC and documentation for high-DTI and high-interest rate applicants.

2. **Push for Short-Term Loans:**
   - Offer better incentives for 36-month loans (e.g., lower rates or faster approval), reducing long-term exposure.

3. **Segmented Products for Debt Consolidation:**
   - Create low-risk, longer-tenure loan bundles tailored to borrowers with strong employment histories.

4. **Predictive Risk Modeling:**
   - Use regression or classification models trained on features like term, purpose, DTI, and employment length to pre-screen applicants.

5. **Geo-Specific Lending Policies:**
   - Adjust interest rates and verification standards based on regional risk performance.

---

## 🧰 Tools & Technologies Used

- **📊 Tableau Public** – Dashboard development and data storytelling
- **🧮 Python (Pandas, NumPy)** – Data preprocessing (offline)
- **📁 loan.csv** – Base dataset containing 30+ borrower and loan fields
- **📄 [Terminology Reference](TERMINOLOGIES%20USED.txt)** – Business-focused data dictionary

---

