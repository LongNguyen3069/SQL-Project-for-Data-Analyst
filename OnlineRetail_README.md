# Online Retail Sales Analytics | SQL Server (T-SQL) & Tableau Public

## Project Overview
This project analyzes online retail transaction data to uncover revenue trends, regional performance drivers, demand seasonality, and targeted marketing opportunities. The goal is to demonstrate end-to-end data analytics skills — from data cleaning and transformation in SQL Server to executive-level dashboarding in Tableau Public — while delivering actionable business insights.

The analysis is framed around leadership-focused business questions commonly faced by sales and marketing teams.

---

## Business Questions
1. **How are sales volume and revenue trending over time, and are there periods of accelerated or declining growth?**
2. **Which products and regions contribute the most to total revenue, and how concentrated is revenue among top performers?**
3. **How does product demand vary by region and season, and where do we observe peak and low demand periods?**
4. **Which products and regions present the greatest opportunity for targeted marketing to drive incremental revenue?**

---

## Dataset
- **Source:** [Online Retail transactional dataset] (https://archive.ics.uci.edu/dataset/352/online%2Bretail?utm_source=chatgpt.com)
- **Grain:** Invoice-level sales transactions
- **Time Period:** 2010–2011
- **Key Fields:** Invoice, Product, Quantity, Unit Price, Revenue, Date, Customer, Country

---

## Data Cleaning & Preparation (SQL Server – T-SQL)
The raw dataset was cleaned and transformed in SQL Server Management Studio to ensure accuracy and analytical readiness.

### Key Cleaning Steps
- Removed records with null or invalid `CustomerID`
- Excluded records with zero or negative `Quantity` or `UnitPrice`
- Standardized date fields and derived calendar attributes
- Created revenue calculations (`Quantity × UnitPrice`)
- Grouped countries into regional categories (UK vs Non-UK)
- Removed non-product administrative records (e.g., bank charges)

### Feature Engineering
- Revenue
- Revenue per Unit
- Invoice Year, Month, Quarter
- Region Grouping

Analytics-ready SQL views were created to support Tableau dashboards without additional transformation.

---

## Analytics Views
The final SQL views aggregate data at appropriate grains for visualization and performance:

- **Time-series performance metrics** (sales volume, revenue, MoM growth)
- **Product and region revenue summaries**
- **Demand and seasonality metrics**
- **Marketing opportunity indicators (revenue concentration, revenue per unit)**

---

## Tableau Dashboards
Interactive dashboards were built in Tableau Public to communicate insights to non-technical stakeholders.

### Dashboard 1: Revenue & Sales Trends
- Revenue and sales volume over time
- Month-over-month growth analysis
- Identification of acceleration and slowdown periods

### Dashboard 2: Revenue Drivers by Product & Region
- Top revenue-generating products and regions
- Revenue concentration analysis (Pareto / 80-20 rule)

### Dashboard 3: Demand Seasonality
- Product demand patterns by region and month
- Identification of peak and low demand periods

### Dashboard 4: Marketing Prioritization
- Revenue per unit by product and region
- High-demand / low-value opportunities for targeted marketing and bundling strategies

---

## Key Insights
- Revenue is highly seasonal, with significant peaks during late-year periods
- A small subset of products contributes a disproportionate share of total revenue
- Demand patterns vary meaningfully by region, suggesting localized marketing strategies
- Certain high-volume regions show lower revenue per unit, indicating pricing or bundling opportunities

---

## Business Recommendations
- Increase inventory planning and marketing spend ahead of peak seasonal periods
- Prioritize top-performing products that drive the majority of revenue
- Implement region-specific promotions during low-demand periods
- Target high-demand, low-revenue-per-unit regions with bundling or pricing optimization

---

## Tools & Technologies
- **SQL Server Management Studio (T-SQL)** — data cleaning, transformation, and analytics views
- **Tableau Public** — data visualization and dashboarding
- **GitHub** — version control and project documentation

---

## Tableau Public Link
👉 https://public.tableau.com/app/profile/long.nguyen6677/viz/OnlineRetailSalesDeepAnalytics/Whichproductsandregionspresentthegreatestopportunityfortargetedmarketing

---

## About This Project
This project was designed to reflect real-world business analytics workflows and demonstrate the ability to translate raw sales data into insights that support leadership decision-making.

Author
Long Nguyen Business Analyst | Data Analytics
