# Week5-Analystlab-Africa

## Telco Customer Churn Analysis (Power BI)

##  Project Overview

This project was completed as part of **Week 5** of the **AnalystLab Africa Data Analytics Internship Program**. The objective was to analyze a telecommunications company's customer churn data using **Power BI** to identify the key factors contributing to customer attrition and provide actionable recommendations to improve customer retention.

The project involved data cleaning, exploratory data analysis (EDA), data modeling, DAX calculations, dashboard development, and business insight generation.

---

#  Business Problem

Customer churn is one of the biggest challenges facing telecommunication companies. Losing customers results in reduced revenue, increased acquisition costs, and lower profitability.

This project aims to answer the following business questions:

* Why are customers leaving the company?
* Which factors contribute the most to customer churn?
* What strategies can the company implement to improve customer retention?

---

#  Dataset Information

**Dataset:** Telco Customer Churn Dataset

The dataset contains **7,043 customer records** with information on:

* Customer demographics
* Service subscriptions
* Contract type
* Internet service
* Payment methods
* Customer tenure
* Monthly charges
* Total charges
* Customer churn status (Yes/No)

---

#  Data Cleaning & Preprocessing

The following data cleaning steps were performed before analysis:

### ✔ Checked for duplicate records

* No duplicate customer records were found.

### ✔ Checked for missing values

* Identified **11 blank values** in the **Total Charges** column.

### ✔ Handled missing values

The 11 blank values were replaced with **0**.

**Reason:**

These customers have a **tenure of 0 months**, meaning they are **new customers** who have not yet completed a billing cycle. As a result, they have **not incurred any total charges**, making **0** a logical and accurate replacement rather than removing the records or imputing another value.

###  Standardized data

* Verified data types
* Ensured consistent formatting
* Removed unnecessary spaces
* Validated numerical columns

---

# Key Performance Indicators (KPIs)

The dashboard includes the following KPIs:

* Total Customers
* Churned Customers
* Churn Rate (%)
* Average Customer Tenure
* Average Monthly Charges

---

#  Dashboard Visualizations

The dashboard includes:

* Customer Churn Distribution
* Customer Churn by Contract Type
* Customer Churn by Tenure
* Customer Churn by Internet Service
* Customer Churn by Payment Method
* Customer Churn by Monthly Charges

---

#  Key Findings

* The company has **7,043 customers**, with **1,869 customers (26.54%)** having churned.
* Customers on **Month-to-Month contracts** recorded the highest churn (**1,655 customers**).
* Customers with **0–12 months** of tenure experienced the highest churn (**1,033 customers**).
* **Fiber Optic** customers accounted for the highest churn (**1,297 customers**).
* Customers using **Electronic Check** as their payment method had the highest churn (**1,071 customers**).
* Customers with higher monthly charges were more likely to leave the company.

---

#  Business Insights

The analysis shows that customer churn is primarily influenced by:

* Contract type
* Customer tenure
* Monthly charges
* Internet service type
* Payment method

Customers with shorter commitments, shorter tenure, and higher monthly charges are significantly more likely to churn.

---

# Recommendations

Based on the analysis, the company should:

* Encourage customers to switch to long-term contracts through loyalty rewards and discounts.
* Improve onboarding and customer engagement during the first year of service.
* Review the pricing and service quality of Fiber Optic plans.
* Encourage customers to adopt automatic payment methods instead of Electronic Checks.
* Implement targeted retention campaigns for high-risk customer segments.

---

# Tools & Technologies

* Power BI
* Power Query
* DAX
* Microsoft Excel

---

# Skills Demonstrated

* Data Cleaning
* Data Validation
* Exploratory Data Analysis (EDA)
* Data Modeling
* DAX Measures
* Dashboard Design
* Data Visualization
* Business Intelligence
* Data Storytelling
* Business Insight Generation

---

# Dashboard Preview

<img width="709" height="375" alt="Telco_Customer_Churn" src="https://github.com/user-attachments/assets/8523bed4-4704-4dbe-83af-f96adf9dae74" />


