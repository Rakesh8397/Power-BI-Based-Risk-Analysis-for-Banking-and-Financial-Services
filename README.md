# Power-BI-Based-Risk-Analysis-for-Banking-and-Financial-Services
This project focuses on developing a risk analytics system for the banking and financial services sector to assist in making data-driven decisions while lending to customers. Using Power BI, we created interactive dashboards that analyze an applicant’s profile to assess the likelihood of loan repayment, thereby minimizing the risk of defaults.
# 📊 Loan Risk Analysis and Approval Decision System Using Power BI

## 📌 Project Overview

This project is designed to demonstrate how data analytics and visualization can be used in the banking and financial services sector to assess credit risk and support decision-making. We used Power BI to create dynamic dashboards that help in identifying whether a loan applicant is likely to repay the loan or not, based on their financial and relationship data.

By understanding the applicant's risk profile, banks can make informed lending decisions and reduce the risk of non-performing assets (NPAs).

---

## 🎯 Problem Statement

Banks often face the risk of financial loss due to defaults by loan applicants. There is a need for a data-driven system that can:

- Evaluate the risk associated with each applicant
- Support automated decision-making for loan approvals
- Help financial advisors and stakeholders visualize and interpret the data clearly

---

## ✅ Solution Approach

We developed interactive Power BI dashboards using the provided dataset, which help in:

- Identifying risky applicants
- Visualizing customer and advisor performance
- Enabling decision-making on loan approvals based on repayment likelihood

If the applicant is low-risk (likely to repay), the dashboard suggests loan approval. If high-risk, the loan may be declined or reviewed further.

---

## 🗂️ About the Dataset

The dataset includes multiple interrelated tables with key attributes related to clients and banking operations:

- **Banking Relationship**  
- **Client-Banking**  
- **Gender**  
- **Investment Advisor**  
- **Period**


---

## 🧼 Data Cleaning Steps

Before visualizing the data, we performed several preprocessing and cleaning tasks to ensure accuracy:

1. **Removed Duplicates:**  
   Eliminated duplicate records from all tables.

2. **Handled Missing Values:**  
   - Null values in categorical columns (e.g., Gender) were filled with a default category like "Unknown".  
   - Numerical nulls were imputed with mean/median values or excluded based on relevance.

3. **Standardized Column Names:**  
   Renamed columns to be consistent, lowercase, and readable (e.g., `Client_ID` → `client_id`).

4. **Data Type Conversion:**  
   Ensured all columns had correct data types (dates, integers, text, etc.).

5. **Filtered Out Irrelevant Records:**  
   Removed inactive clients or historical periods not relevant to analysis.



---

## 🧰 Tools & Technologies Used

- **Power BI** (Data Modeling, Power Query, Dashboard Creation)
- **Microsoft Excel** (Preliminary Cleaning)
- **SQL** for querying and merging prior to import

---

## 📈 Key Dashboards and Insights

- **Client Risk Profile View**  
- **Loan Approval Suggestions Based on Risk Score**  
- **Advisor Performance Metrics**  
- **Gender and Age Group Trends**  
- **Banking Relationships and Client Engagement**
- !Dashboard image![Screenshot 2025-07-04 120118](https://github.com/user-attachments/assets/643e6286-d8ab-45ee-bc9d-1cebf841380e)


---

## 📌 Outcomes

- Helped simulate real-world credit risk analytics
- Enabled better decision-making for financial institutions
- Improved understanding of client and advisor relationships
- Built an end-to-end BI solution from raw data to insights

---



