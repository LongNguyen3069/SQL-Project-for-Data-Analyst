# Global Advertising Performance Analysis (Excel)

## Project Overview

This project analyzes 1,800+ rows of global digital advertising performance data to evaluate return on ad spend (ROAS), cost efficiency, and profitability across platforms, industries, countries, and campaign types.

The objective is to demonstrate end-to-end analytical skills in data cleaning, validation, KPI analysis, pivot tables, and dashboard design using Microsoft Excel.

---

## Tools and Technologies

- Microsoft Excel  
  - Data cleaning and validation  
  - Formulas and feature engineering  
  - Pivot Tables and Pivot Charts  
  - Dashboard design  

---

## Dataset Description

The dataset contains daily advertising performance records with the following key fields:

- Date  
- Platform  
- Campaign Type  
- Industry  
- Country  
- Impressions  
- Clicks  
- CTR (Click-Through Rate)  
- CPC (Cost Per Click)  
- Ad Spend  
- Conversions  
- CPA (Cost Per Acquisition)  
- Revenue  
- ROAS (Return on Ad Spend)  

Total Records: 1,800+

---

## Data Cleaning and Preparation

Key steps performed in Excel:

- Standardized data types for dates, text, and numeric fields  
- Trimmed and validated categorical fields  
- Recalculated and validated key KPIs:
  - CTR = Clicks / Impressions  
  - CPC = Ad Spend / Clicks  
  - CPA = Ad Spend / Conversions  
  - ROAS = Revenue / Ad Spend  

- Flagged invalid and inconsistent records:
  - Clicks greater than Impressions  
  - Conversions greater than Clicks  
  - Zero or negative values  

- Engineered new analytical features:
  - Month (for time-series analysis)  
  - Profit = Revenue - Ad Spend  
  - Profit Margin  
  - Performance Buckets based on ROAS  

---

## Analysis and Pivot Tables

The following core analyses were built using Pivot Tables:

1. Platform Performance  
   - Total Ad Spend  
   - Total Revenue  
   - Total Conversions  
   - Average ROAS  

2. Industry ROI Ranking  
   - Average ROAS by Industry (sorted descending)  

3. Top 10 Countries by Revenue  
   - Geographic concentration of revenue and spend  

4. Campaign Type Efficiency  
   - Average CTR vs Average CPA (Combo Chart with secondary axis)  

5. Monthly Performance Trends  
   - Revenue, Spend, and ROAS over time  

---

## Dashboard Design

A single-page executive-style dashboard was created featuring:

- KPI cards:
  - Total Ad Spend  
  - Total Revenue  
  - Overall ROAS  
  - Total Conversions  

- Charts:
  - Revenue vs Ad Spend by Platform  
  - Industry Ranking by Average ROAS  
  - Top 10 Countries by Revenue  
  - Campaign Type Efficiency (CTR vs CPA Combo Chart)  
  - Monthly Performance Trend  

The dashboard is designed to quickly answer:

- Where is money being spent?  
- Where is revenue being generated?  
- Which segments are efficient versus inefficient?  
- How is performance changing over time?  

---

## Key Insights (Example)

- Identified platforms with high spend but low ROAS as optimization candidates  
- Highlighted industries with strong ROAS but underinvestment  
- Found geographic markets driving a disproportionate share of revenue  
- Observed campaign types with high CTR but high CPA, indicating funnel inefficiencies  

---

## Sheets in This Excel

- `global_ads_performance_dataset` — Original dataset  
- `Working sheet` — Cleaned and validated dataset  
- `Pivot tables` — Pivot tables and analysis  
- `Dashboard` — Final Excel dashboard  

---

## Skills Demonstrated

- Data cleaning and validation  
- Feature engineering  
- KPI development  
- Pivot table analysis  
- Business-focused dashboard design  
- Data storytelling  

---

## Contact

Long Nguyen  
Aspiring Data Analyst  
lnguyenlhn@gmail.com

- LinkedIn: https://www.linkedin.com/in/long-nguyen-0b406616a/
- Tableau Public: https://public.tableau.com/app/profile/long.nguyen6677/vizzes
