# Paisabazaar Credit Score Analysis – EDA + Power BI Dashboard  


## 📖 Project Overview
This project focuses on analyzing customer credit behavior and financial health using **Exploratory Data Analysis (EDA)** in Python and building interactive **Power BI dashboards** for visualization.  
The dataset includes customer demographics, credit utilization, delayed payments, income, and loan details.  

The analysis provides insights into:
- Customer demographics (age, income, occupation, credit score distribution).
- Credit behavior and loan repayment patterns.
- Risk assessment through delayed payments and utilization ratio.
- Financial health indicators for better decision-making.

---

## 🔧 Tools & Technologies
- **Python**: Numpy, Pandas, Matplotlib, Seaborn (for EDA & preprocessing)  
- **Power BI**: Dashboard design & visualization  
- **Data Manipulation**: Filtering, cleaning, and transformation  

---

## 🧹 Data Manipulations Performed
1. **Removed rows with `Num_of_Loan = 0`**  
   - Focuses only on customers actively engaged in credit activities.

2. **Removed rows with `Num_of_Loan = 1` and `Type_of_Loan = "Not specified"`**  
   - Ensures loan insights are based on clearly defined loan types.

3. **Removed rows with `Payment_of_Min_Amount = "NM"` (Not Mentioned)**  
   - Keeps only valid customer payment behavior for accurate insights.

4. **Replaced numeric month values with month names**  
   - Improved readability for trend analysis across months.

---

## 📊 Dashboards Created

1. **Overview & Customer Demographics**  
   - Total customers, age distribution, income by occupation, and credit score segments.
     <img width="1283" height="710" alt="Screenshot 2025-09-30 164415" src="https://github.com/user-attachments/assets/aefcb2a7-fe3f-4f33-b7af-df03dc5feb24" />

2. **Credit Behavior & Risk Assessment**  
   - Loan distribution, delayed payments, outstanding debt, and utilization ratios.
      <img width="1276" height="724" alt="Screenshot 2025-09-30 164446" src="https://github.com/user-attachments/assets/e173ebec-ce4c-454c-b063-a1827d4fad26" />

3. **Financial Health & Investment Trends**  
   - Identified customer groups with higher financial risks vs. stable profiles.
     <img width="1264" height="733" alt="Screenshot 2025-09-30 164722" src="https://github.com/user-attachments/assets/a3fb1545-99c5-46c2-a311-f8eef642abf1" />


---

## 📈 Key Insights
- Average customer age is **32.9 years**, with an average income of **₹48.6K**.  
- Only **16% of customers** have a good credit score, while **31% are poor**.  
- Customers with poor credit scores show **higher outstanding debts** and **loan delays**.  
- Occupations like **Entrepreneurs, Architects, and Writers** have the highest average incomes.  

---

## 📂 Project Structure
- `code/` → Python scripts for cleaning and visualization.  
- `powerbi/` → Power BI files (.pbix).  
- `source files/` → Source files for Python file.  

---
## 📌 Results
This project helps financial institutions understand customer **credit health, loan behavior, and risk assessment**, enabling better decision-making for **loan approvals, credit limits, and personalized financial advice**.

---

## 🔗 Demo
- Power BI Dashboard Screenshots included in `/Reports`  
- Sample Insights available in documentation.

---
