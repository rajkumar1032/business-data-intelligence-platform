# Business Data Intelligence Platform

An end-to-end retail data analytics project using Python and Pandas to transform transaction data into actionable business insights.

## Project Overview

This project analyses the UCI Online Retail dataset to explore revenue trends, product performance, country-level sales, customer behaviour, and data quality.

## Key Findings

- **Net Revenue:** £9.73 million
- **Top Market:** United Kingdom, contributing approximately 84% of net revenue
- **Peak Revenue Month:** November 2011
- **Identified Customers:** 4,372
- **Repeat Customers:** 3,059 (approximately 70% of identified customers)

*Note: December 2011 contains partial-month data. Customer metrics exclude transactions without a CustomerID.*

## Project Workflow

1. Data loading and inspection
2. Data quality assessment
3. Duplicate transaction removal
4. Revenue and exploratory data analysis
5. Product and country performance analysis
6. Customer behaviour and concentration analysis
7. Data validation and CSV report generation

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Dataset

**Source:** [UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)

The dataset contains transactions from a UK-based online retailer between December 2010 and December 2011.

## Business Value

This project demonstrates how retail transaction data can be used to identify sales trends, key markets, customer behaviour, product performance, and data quality issues.

## Limitations

- Missing CustomerIDs limit customer-level analysis.
- Negative quantities may represent returns or cancellations.
- December 2011 is incomplete and should not be compared directly with full months.
- Product rankings may exclude postage and other non-standard items.

---

**Project Type:** Exploratory Data Analysis and Business Intelligence  
**Status:** Portfolio Project
