# NovaMart — Revenue Leakage & Pricing Anomaly Detection System

## Project Overview

NovaMart is an end-to-end Data Analytics portfolio project based on a fictional e-commerce business. It investigates potential revenue leakage and pricing-related anomalies through data preparation, SQL analysis, and interactive Power BI dashboards.

## Business Objective

Analyze transaction data to identify records that may require further investigation, including:

- Discounts exceeding product-specific limits
- Transactions with low profit margins
- Shipping costs exceeding the defined threshold
- Large refunds requiring review
- Potential duplicate transactions

## Tools & Technologies

- **Python:** Data processing and analysis
- **Pandas & NumPy:** Data manipulation
- **MySQL:** SQL queries and data validation
- **Excel:** Data inspection and analysis
- **Power BI:** Interactive dashboards and KPI reporting

## Project Workflow

1. Generate and validate synthetic e-commerce datasets.
2. Prepare data for analysis using Python.
3. Load data into MySQL and investigate business-rule exceptions.
4. Analyze potential anomalies and transaction patterns.
5. Build Power BI dashboards for business performance and risk investigation.
6. Communicate findings for further review and decision-making.

## Dashboard Pages

### 1. Sales Performance
Sales, profit, profit margin, monthly trends, category performance, and channel contribution.

### 2. Risk & Investigation Center
Potential discount anomalies, low-margin transactions, shipping-cost checks, and large refunds.

### 3. Business Performance
Regional performance, product-category profitability, sales channels, and interactive filtering.

## Data Disclaimer

This project uses synthetic data for a fictional business. Flagged records represent potential anomalies for investigation and do not establish confirmed financial losses or fraud.

## Repository Contents

- `data/` — Synthetic datasets and processed analysis data
- `scripts/` — Python data-generation, validation, and analysis scripts
- `sql/` — SQL analysis queries
- `reports/` — Dashboard screenshots and Power BI report, where included

## Future Improvements

- Add automated data-quality checks
- Improve anomaly validation and reconciliation
- Expand dashboard reporting and business recommendations.
- 
