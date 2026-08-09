## Part 1: Business Understanding Report

## Telco Customer Churn Analysis

### 1. Business Context

Customer retention is an important factor in the telecommunications industry. Companies invest significant resources in attracting new customers, making it important to understand why existing customers leave and what can be done to encourage them to stay.

Customer churn occurs when a customer stops using a company's services or terminates their subscription.

For this project, the focus is on analysing customer data from a telecommunications company to understand customer behaviour and identify patterns associated with churn.

---

### 2. The Business Problem

The company is experiencing customer churn and needs to better understand the characteristics and behaviours of customers who leave compared with those who remain.

A high churn rate can result in:

- Loss of recurring revenue

- Increased customer acquisition costs

- Reduced customer lifetime value

- Difficulty maintaining a stable customer base

- Potential weaknesses in pricing, service delivery, or customer experience

The business therefore needs data-driven insights to identify customers or customer groups that may be more likely to churn.

---

### 3. Why do customers leave?
Customers may leave a telecommunications company for different reasons, including:

* High or unexpected charges
* Poor service experience
* Lack of technical support
* Unsuitable contract terms
* Limited service options
* Better offers from competitors
* Short customer tenure and low commitment


### 4. Understanding the Dataset

The dataset contains information about customers and the services they use.

It includes variables covering:

**Customer information**

- Customer ID

- Gender

- Senior Citizen status

- Partner status

- Dependents

**Customer tenure and charges**

- Tenure

- Monthly Charges

- Total Charges

**Services**

- Phone Service

- Internet Service

- Online Security

- Online Backup

- Device Protection

- Tech Support

- Streaming TV

- Streaming Movies

**Account information**

- Contract

- Paperless Billing

- Payment Method

**Outcome variable**

- Churn

The dataset contains **7,043 customer records**.

---

### 5. Business Questions

The analysis will answer the following questions:

#### Customer Churn

- What percentage of customers have churned?

- How many customers have remained with the company?

- Which customer groups experience the highest churn?

#### Customer Tenure

- Does customer tenure influence churn?

- Are newer customers more likely to leave?

- Do long-term customers show stronger retention?

#### Contract Type

- Which contract type has the highest churn?

- Are customers on month-to-month contracts more likely to leave?

- Does longer contract commitment appear to support retention?

#### Payment Method

- Which payment methods are associated with higher churn?

- Do electronic check customers churn more than customers using other payment methods?

#### Customer Services

- Does internet service type relate to churn?

- Are customers without additional support services more likely to leave?

- Do customers using multiple services show different retention patterns?

#### Customer Charges

- Is there a relationship between monthly charges and churn?

- How are monthly charges related to total charges?

- Do customers with higher charges show different churn behaviour?

#### Customer Demographics

- Does gender have a meaningful relationship with churn?

- Are senior citizens more likely to churn?

- Does having a partner or dependents appear to influence retention?

---

### 6. Analytical Approach

The analysis will follow a structured process.

**Step 1: Data Inspection**

The dataset will first be examined to understand its structure, identify missing values, check data types, and identify potential data quality issues.

**Step 2: Data Cleaning**

Issues identified during inspection will be addressed to ensure the dataset is suitable for analysis.

This includes checking missing values, reviewing inconsistent entries, and ensuring numerical fields are correctly formatted.

**Step 3: Exploratory Data Analysis**

Pivot Tables and charts will be used to examine customer behaviour and compare churn across different customer segments.

Key variables such as tenure, contract type, payment method, monthly charges, total charges, and services will be analysed.


**Step 4: Identify Insights**

The analysis will highlight the customer groups with the highest churn and identify patterns that may help explain customer retention and churn.

**Step 5: Business Recommendations**

The findings will be translated into practical recommendations that the company can consider when developing customer retention strategies.

---

### 7. Definition of Success

The analysis will be considered successful if it provides a clear understanding of:

## Who is leaving? 

Identifying the customer segments with the highest churn.

## What patterns are associated with churn?   

Understanding how tenure, contracts, payment methods, services, charges, and customer characteristics relate to churn.

## What can the business do?  

Providing specific and actionable recommendations based on the findings.

---

## Summary

* Business Problem: The telecommunications company is experiencing customer churn.

* Objective: Understand customer behavior and identify factors associated with customers leaving.

* Approach: Inspect, clean, analyze, visualize, and interpret customer data.

* Expected Outcome: Data-driven insights and practical recommendations that can support customer retention.

Next: Part 2 – Dataset Inspection and Data Quality Assessment.
