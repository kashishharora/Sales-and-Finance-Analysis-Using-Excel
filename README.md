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
