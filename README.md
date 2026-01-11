# Home Credit Risk Analysis

This repository contains an end-to-end **Credit Risk Analytics** project developed using **SQL**, **Python**, and **Power BI**.  
The project demonstrates how **multi-table financial data** can be transformed into actionable insights through **risk segmentation**, **behavioural analysis**, and **policy-driven scenario modelling**.

---

## Overview

The objective of this project is to analyse credit risk at a portfolio level, identify high-risk customer segments, and evaluate how changes in credit policy thresholds impact approval volumes and default risk.

The analysis follows a structured, end-to-end workflow:
- **SQL-based data integration and feature engineering**
- Exploratory analysis and validation
- Interactive **Power BI** dashboards for insight delivery and decision support

---

## Tools & Technologies

- **SQL** – multi-table joins, aggregations, feature engineering, analytical views  
- **Python** – data exploration and preprocessing  
- **Power BI** – DAX measures, KPI design, segmentation analysis, what-if scenario modelling  

---

## Data Source

This project uses the **Bank Loan Case Study Dataset** from Kaggle (multi-table credit data):

**https://www.kaggle.com/datasets/shreshthvashisht/bank-loan-case-study-dataset**

The dataset consists of multiple relational tables capturing:
- Customer applications  
- Historical loan activity  
- Credit and behavioural attributes  
- Default outcomes  

These raw tables were **integrated in PostgreSQL using SQL joins and aggregations** to construct a **customer-level analytical base table** containing:
- Demographics (age, income)  
- Credit characteristics (loan amount, interest rate, credit-to-income ratio)  
- Behavioural indicators (previous application counts, refused application counts, average previous credit exposure)  
- The default outcome variable  

Due to GitHub file size limitations, the prepared analytical dataset is provided in compressed form.  
All files can be extracted locally to reproduce the SQL pipeline, Power BI dashboards, and analytical results.

---
## Repository Structure

home_credit/
│
├── data/ # Dataset files (compressed)
├── images/ # Dashboard screenshots
├── power bi/ # Power BI PBIX files
├── report/ # Final analytical report
└── README.md

---

## Analysis Overview

The analysis focuses on three core areas:

### 1. Executive Risk Overview
![Executive Risk Overview](images/home_credit-1.png)
- Portfolio-level default rate
- Distribution of high-risk customers
- Overall affordability and exposure indicators
  

### 2. Customer Risk Segmentation
![Customer Risk Segments](images/home_credit-2.png)

- Default risk by age and income bands
- Behavioural risk driven by previous credit refusals
- Identification of concentrated risk pockets

### 3. Policy & Scenario Analysis
![Policy & Scenario Analysis](images/home_credit-3.png)
- Credit-to-income (CTI) threshold evaluation
- Trade-offs between approval volume and default risk
- Identification of policy inflection points

---

## Key Insights

- Portfolio-level default rates mask concentrated risk within specific customer segments  
- Younger customers in lower income bands exhibit disproportionately higher default risk  
- Previous credit refusals are a strong behavioural predictor of future default  
- Relaxing credit policy thresholds increases approvals but accelerates default risk beyond optimal levels  

---

## Recommendations

- Apply **segment-based credit policies** rather than uniform thresholds  
- Incorporate **behavioural risk signals** (e.g. previous refusals) into decision-making  
- Optimise CTI thresholds to balance growth objectives and risk exposure  
- Monitor segment-level performance continuously through dashboards  

---

## Dashboards

The project includes interactive Power BI dashboards covering:
- Executive Risk Overview
- Customer Risk Segmentation
- Policy & Scenario Analysis

Dashboard screenshots are available in the `images` folder, and PBIX files are included for local exploration.

---

## Contact

- **Portfolio Website:** https://azed.uk  
- **LinkedIn:** https://linkedin.com/in/soroush-azed  
- **Email:** soroush.azed@gmail.com  
