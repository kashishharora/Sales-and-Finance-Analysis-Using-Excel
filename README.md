# Customer Sales & Market Performance Analytics

## Project Description

This project analyzes customer sales growth and market performance using Excel, Power Query, Power Pivot, and DAX.
It covers 3 fiscal years of AtliQ Hardwares data to track net sales trends, target achievement, and profitability (COGS, Gross Margin) across markets and product divisions.

## Overview

This project analyzes 3 fiscal years (FY 2019–2021) of AtliQ Hardwares sales data across 23+ global markets.
The reports provide insights into:

- Customer-wise net sales growth from FY 2019 to FY 2021
- Market performance vs. sales targets for FY 2021
- Profitability analysis (Net Sales, COGS, Gross Margin %) by market
- Yearly and quarterly P&L trends
- Top 10 fastest-growing products (2021 vs 2020)

## Business Problem

- Track customer-level sales growth and identify top contributors
- Compare market sales vs. targets to find performance gaps
- Evaluate profitability differences across markets
- Identify fastest-growing products to guide future strategy

## Tools & Technologies

- **Microsoft Excel** — Report creation & formatting
- **Power Query** — Importing, cleaning, and transforming raw data
- **Power Pivot** — Data modeling and managing large datasets
- **Pivot Tables** — Summarizing customer, market, and product performance
- **DAX Measures** — Built KPIs such as Net Sales, Gross Margin %, YoY Growth %, Target Achievement %
- **Date Table** – extracted Year, Quarter, Month from order dates for trend analysis.
- **Conditional Formatting** — Highlighting key values and trends for quick visual analysis
  
## Data Cleaning & Preparation
### Power Query:
- Removed duplicates and invalid records
- Standardized data formats (Date, Currency, Percentage)
- Created a custom Date Table and extracted: Year, Quarter, Month

### Power Pivot & Data Modelling:
- Established relationships between tables: Customer ↔ Sales , Market ↔ Sales , Product ↔ Sales , Date ↔ Sales
- Built a Star Schema for flexible, scalable reporting

### DAX Measures Created:

- Net Sales | COGS | Gross Margin | GM % | 21 vs 20 % | Target Achievement %

### Data Model Screenshot — included in repository

## Key Findings
- **Customer Growth**: 67 customers tracked across FY 2019–2021 — top performers include Amazon ($12.2M → $82.1M, +218.9%), AtliQ Exclusive ($9.6M → $61.1M, +345.8%), AtliQ eStore ($7.2M → $53.0M, +223.8%), and Flipkart ($2.9M → $19.3M, +231.0%) — overall grand total grew from $87.5M → $598.9M (+304.5%)
- **Market Performance vs Target (FY 2021)**: All 23 markets missed their 2021 sales targets — overall shortfall of $54.9M (-9.2%), worst being Poland (-18.1%), Canada (-14.5%), Spain (-14.1%), while Japan (-4.1%) performed closest to target.
- **Sales Trend**: Net Sales grew rapidly from $87.5M (2019) → $196.7M (2020) → $598.9M (2021) — a +124.8% (20 vs 19) and +204.5% (21 vs 20) YoY growth
- **Top 10 Products(2021 vs 2020)**:
- AQ Mx NB ($0.0M → $1.4M, +5,621%), AQ Smash 2 ($0.4M → $11.2M, +2,490%), and AQ LION x3 ($0.1M → $1.2M, +1,693%) showed exceptional growth
- Top 10 products combined grew from $6.4M → $52.0M (+708% YoY)

## Report Highlights
- Customer Net Sales Report (2019–2021) — Customer-wise sales and growth across 67 customers
- Market Performance vs Target (2021) — Actual vs. target gap analysis across 23 markets
- P&L by Market — Net Sales, COGS, Gross Margin % — GM% ranged from 26.2% (Germany) to 48.2% (New Zealand)
- P&L by Fiscal Year — Yearly and quarterly sales trend (2019–2021)
- Top 10 Products (2021 vs 2020) — Fastest-growing products — led by AQ Mx NB (+5,621%)

## Final Recommendations

- Strengthen focus on top-growing customers like Amazon and AtliQ Exclusive
- Investigate reasons for missed targets in large markets like USA, India, and Canada
- Replicate strategies from high-margin markets like Japan and New Zealand
- Improve low-margin markets such as Germany and Norway
- Invest in top-performing products like AQ Mx NB, AQ Smash 2, and AQ LION series to sustain growth
- Monitor customer, market, and product trends quarterly for better decision-making

## Author & Contact

- Author: Kashish Arora
- Email: arorakashish224@gmail.com
- LinkedIn: www.linkedin.com/in/kashisharora12
