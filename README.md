# 💳 Paisabazaar Credit Score EDA (Python + Power BI)

---

## 🧩 1. Problem Statement
This project aims to analyze customer financial and behavioral data to identify the key factors influencing credit scores.  
The goal is to help financial institutions assess creditworthiness, reduce default risks, and provide personalized financial recommendations to customers.

---

## 📁 2. Data Overview

### a. Data Description
The dataset contains detailed financial and behavioral information for customers, collected from credit reports and financial profiles.  
It is used to explore how different attributes—such as income, payment behavior, and credit utilization—affect a customer’s credit score category.

### b. Data Fields

| Column Name | Description |
|--------------|-------------|
| `ID` | Unique record identifier |
| `Customer_ID` | Unique identifier assigned to each customer |
| `Month` | Month of record entry |
| `Name` | Customer name (anonymized for privacy) |
| `Age` | Age of the customer |
| `SSN` | Masked Social Security Number / Identification |
| `Occupation` | Employment type or occupation category |
| `Annual_Income` | Total yearly income of the customer |
| `Monthly_Inhand_Salary` | Net monthly take-home salary |
| `Num_Bank_Accounts` | Total number of active bank accounts |
| `Num_Credit_Card` | Total number of credit cards held |
| `Interest_Rate` | Average interest rate applicable to customer’s loans or credit cards |
| `Num_of_Loan` | Number of active loans (home, car, education, etc.) |
| `Type_of_Loan` | Categories of loans the customer holds |
| `Delay_from_due_date` | Average number of days payment is delayed beyond the due date |
| `Num_of_Delayed_Payment` | Number of instances where payment was delayed |
| `Changed_Credit_Limit` | Indicates whether the credit limit has changed recently |
| `Num_Credit_Inquiries` | Number of recent credit or loan inquiries made by the customer |
| `Credit_Mix` | Composition of different credit types (Good, Standard, or Bad) |
| `Outstanding_Debt` | Total unpaid debt across all accounts |
| `Credit_Utilization_Ratio` | Ratio of used credit to total available credit limit |
| `Credit_History_Age` | Duration of credit history (in months/years) |
| `Payment_of_Min_Amount` | Indicates if the customer only pays the minimum amount due (Yes/No) |
| `Total_EMI_per_month` | Total monthly EMI payments for loans and credit cards |
| `Amount_invested_monthly` | Average amount the customer invests each month |
| `Payment_Behaviour` | Pattern of payments (e.g., on time, delayed, irregular) |
| `Monthly_Balance` | Remaining balance after all expenses and EMIs are paid |
| `Credit_Score` | Categorized score (Good, Standard, or Poor) |

---

## ⚙️ 3. Approach
1. **Data Cleaning:**  
   - Removed records with missing or invalid values.  
   - Filtered out customers with `Num_of_Loan = 0` to focus on active credit users.  
   - Normalized income and debt values for consistent scaling.  

2. **Exploratory Data Analysis (EDA):**  
   - Conducted univariate and bivariate analysis using **Python** (`pandas`, `matplotlib`, `seaborn`).  
   - Explored the relationships between `Credit_Score` and other key attributes like income, utilization ratio, and payment behavior.  

3. **Feature Analysis:**  
   - Examined the impact of delayed payments, outstanding debt, and credit mix on credit score distribution.  

4. **Visualization (Power BI):**  
   - Built interactive dashboards showing score distribution, income patterns, credit utilization, and customer risk segmentation.  

---

## 📈 4. Results
- Customers with **Credit Utilization Ratio > 50%** and frequent delays tend to fall in the **Poor credit score** segment.  
- **Payment consistency** and **lower debt-to-income ratio** are key drivers of **Good credit scores**.  
- Identified that **occupation type** and **monthly balance** also influence creditworthiness.  
- Provided actionable insights for credit policy improvements and customer risk monitoring.

---

## 🖥️ 5. Output
### Power BI Dashboard  
Overview and Customer Demographics

<img width="1158" height="643" alt="Screenshot 2025-09-25 161834" src="https://github.com/user-attachments/assets/db66017e-a0ae-4f8f-8ef5-0154b6544fb9" />

Credit behaviour and Risk Assessment

<img width="1146" height="654" alt="Screenshot 2025-09-25 161925" src="https://github.com/user-attachments/assets/bef3cb8a-0645-4a5d-917b-209d3248dfce" />

Financial Health and Investment

<img width="1133" height="650" alt="Screenshot 2025-09-25 162013" src="https://github.com/user-attachments/assets/54e39be8-a572-463c-8867-d4d2f6b7871e" />


**Key Visuals:**  
- 📊 Credit Score Distribution (Good / Standard / Poor)  
- 💰 Income vs Credit Score Analysis  
- 📈 Credit Utilization & Debt Correlation  
- 🏦 Loan Type and Count by Credit Category  
- 🧮 Payment Behavior and Delay Trends  

---

## 🧾 6. Conclusion
The Paisabazaar Credit Score EDA revealed strong relationships between financial discipline and creditworthiness.  
It helped identify patterns that contribute to poor scores, enabling targeted interventions for customer financial improvement.  

**Future Enhancements:**  
- Develop a **predictive machine learning model** for credit score classification.  
- Integrate **real-time data** from financial APIs for continuous monitoring.  
- Build a **recommendation system** for improving individual credit health.

---

## 🧠 Tools & Technologies Used
- **Python:** Data Cleaning & EDA (`numpy`,`pandas`, `matplotlib`, `seaborn`)  
- **Power BI:** Visualization and dashboard design  
- **Excel / CSV:** Source data preparation  
- **Data Modeling:** Feature analysis and metric correlation  

---

