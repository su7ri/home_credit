# Home Credit Risk Analysis

This repository contains an end-to-end **Credit Risk Analytics** project developed using **SQL**, **Python**, and **Power BI**.  
The project demonstrates how multi-table financial data can be transformed into actionable insights through **risk segmentation**, **behavioural analysis**, and **policy-driven scenario modelling**.

---

## Overview

The objective of this project is to analyse credit risk at a portfolio level, identify high-risk customer segments, and evaluate how changes in credit policy thresholds impact approval volumes and default risk.

The analysis follows a structured, end-to-end workflow:
- SQL-based data preparation and feature engineering
- Exploratory analysis and validation
- Interactive Power BI dashboards for insight delivery and decision support

---

## Tools & Technologies

- **SQL** – joins, aggregations, feature engineering, analytical views  
- **Python** – data exploration and preprocessing  
- **Power BI** – DAX measures, KPI design, segmentation analysis, what-if scenario modelling  

---

## Data Source

This project uses a publicly available credit risk dataset from Kaggle:

https://www.kaggle.com/datasets/laotse/credit-risk-dataset  

The dataset contains anonymised consumer lending records, including customer demographics, financial attributes, behavioural indicators, and default outcomes.

Due to GitHub file size limitations, the raw dataset has been compressed and uploaded as a ZIP archive.  
All data files can be extracted locally to reproduce the analysis and dashboards.

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
![Executive Risk Overview](images/executive-risk-overview.png)
- Portfolio-level default rate
- Distribution of high-risk customers
- Overall affordability and exposure indicators
  

### 2. Customer Risk Segmentation
![Customer Risk Segments](images/customer-risk-segments.png)

- Default risk by age and income bands
- Behavioural risk driven by previous credit refusals
- Identification of concentrated risk pockets

### 3. Policy & Scenario Analysis
![Policy & Scenario Analysis](images/policy-scenario-analysis.png)
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
