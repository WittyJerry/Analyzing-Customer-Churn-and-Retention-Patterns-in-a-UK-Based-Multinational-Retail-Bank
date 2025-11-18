# Analyzing Customer Churn and Retention Patterns in a UK-Based Multinational Retail Bank

---

## Table of Contents
- [Project Overview](#project-overview)
- [Business Introduction](#business-introduction)
- [Business Problem](#business-problem)
- [Rationale for the Project](#rationale-for-the-project)
- [Aim of Project](#aim-of-project)
- [Project Objectives](#project-objectives)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results / Findings](#results--findings)
- [Recommendations](#recommendations)
- [Key Achievements](#key-achievements)
- [Value Delivered](#value-delivered)
- [Limitations](#limitations)
- [References](#references)

---

## Project Overview
This project analyzed customer churn at **Veritas Bank**, a UK-based multinational retail bank, using **SQL Server** and **Power BI**.  
The analysis integrated demographics, tenure, product usage, and credit scores to identify high-risk segments and enable data-driven retention strategies.  
Insights informed executive-level decision-making and regional marketing interventions.

---

## Business Introduction
**Veritas Bank**, headquartered in London, UK, operates across the UK, Germany, and France, serving over **3 million retail customers**.  
The bank offers savings, personal loans, debit/credit cards, and online banking services.  
Facing rising competition from fintech and neobanks, Veritas needed to understand churn patterns and improve retention strategies.

---

## Business Problem
Challenges included:
- Rising churn, particularly in Germany and France  
- Limited real-time monitoring and segmentation of customers  
- Declining engagement in continental Europe  
- Competition from neobanks and digital-first challengers  

**Impact:**
- Revenue loss from departing customers  
- Missed opportunities for targeted retention  
- Reduced customer lifetime value  

---

## Rationale for the Project
The project was designed to:
- Identify churn drivers using customer behavioral and demographic data  
- Segment customers by risk profile  
- Enable personalized engagement and retention strategies  
- Provide leadership with actionable dashboards for decision-making  

---

## Aim of Project
To analyze and predict customer churn patterns, identify high-risk segments, and provide executive dashboards that guide retention initiatives across the UK, Germany, and France.

---

## Project Objectives
- Detect common characteristics of churned customers  
- Compare churn across regions, age groups, and tenure levels  
- Segment customers by product usage and credit score  
- Visualize churn metrics to support strategic decisions  
- Enable targeted retention campaigns for high-risk segments  

---

## Data Sources
**Customer Data (Veritas Dataset):**
- CustomerId, LastName, Gender, Age, Country  
- Tenure, Balance, Number of Products  
- CreditScore, HasCrCard, IsActiveMember  

---

## Tools Used
- **Microsoft SQL Server:** Data storage, cleaning, and querying  
- **Microsoft Power BI:** Dashboard development, visualization, and DAX modeling  
- **PowerPoint:** Presentation of insights and recommendations  

---

## Data Cleaning & Preparation
- Imported and validated 10,000 customer records  
- Standardized country, age, and tenure values  
- Created derived columns: tenure buckets, credit score categories, product count groups  
- Removed duplicates and handled missing data  

---

## Exploratory Data Analysis
- Analyzed customer distribution by country, age, and gender  
- Reviewed active vs inactive members  
- Examined correlations between tenure, product usage, balance, credit score, and churn  

---

## Data Analysis
- Built DAX measures in Power BI for churn calculation  
- Developed Sankey diagrams to visualize churn flows  
- Segmented high-risk customers by country, tenure, and credit score  
- Analyzed churn trends by product count and account balance  

---

## Results / Findings

### Customer Demographics & Segmentation

**Customer Demographic Dashboard:**
![Customer Demographic Dashboard](https://github.com/WittyJerry/Analyzing-Customer-Churn-and-Retention-Patterns-in-a-UK-Based-Multinational-Retail-Bank/blob/main/Customer%20demographics.png)

- Total Customers: **10,000**  
- Avg Credit Score: **651**  
- Avg Balance: **£27K**  
- Active Members: **52%**  
- Country Split: UK **50%**, Germany **25%**, France **25%**  
- Gender: Male **56.4%**, Female **43.6%**  

### Churn Analysis

**Customer Churn Analysis Dashboard:**
![Customer Churn Analysis Dashboard](https://github.com/WittyJerry/Analyzing-Customer-Churn-and-Retention-Patterns-in-a-UK-Based-Multinational-Retail-Bank/blob/main/Customer%20churn%20analysis.png)
- Total Churned: **1,385 (14% overall)**  
- Germany: Highest churn (**28%**)  
- Age 40–60: Most churn-prone  
- Tenure <3 years: Higher churn risk  
- Single-product customers: Strong churn predictor  
- Low balance & fair credit scores: Highest churn  

### Sankey Flow Highlights
- UK churned males with inactive status and fair credit scores were most at risk  
- Visualization confirmed behavioral and demographic churn patterns  

---

## Recommendations
- Launch retention campaigns targeting high-risk segments in Germany and France  
- Implement personalized offers based on tenure, credit score, and product usage  
- Use dashboards for continuous churn monitoring  
- Encourage engagement of inactive members to reduce churn risk  

---

## Key Achievements

| Challenge | Action Taken | Impact |
|-----------|--------------|--------|
| High churn in Germany & France | Segmented churn by region, age, tenure, and product usage | Enabled targeted retention campaigns |
| Lack of real-time insights | Built Power BI dashboards with filters and KPIs | Equipped leadership with actionable metrics |
| No customer segmentation | Created risk profiles using SQL and DAX | Improved personalization and engagement |

---

## Value Delivered
- Reduced churn risk by identifying high-risk customer segments  
- Enabled targeted retention campaigns by region  
- Delivered executive dashboards for strategic planning  
- Strengthened Veritas Bank’s competitive positioning in Europe  

---

## Limitations
- Analysis was based on a subset of 10,000 customers and limited behavioral data, which may not fully represent the full customer base  
- Timeframe and external factors (market trends, competition) were not fully captured  
- Insights are descriptive; predictive modeling was not applied, so churn probabilities for individuals were not calculated  

---

## References
- Veritas Bank Annual Reports (2022–2024) – Financial and customer data insights  
- [Microsoft Power BI Documentation](https://docs.microsoft.com/power-bi/)  
- [Microsoft SQL Server Documentation](https://docs.microsoft.com/sql/)  
