# Retail Sales & Profitability Analysis | Tableau Dashboard

## Project Overview

This project uses Tableau to explore retail sales and profitability across product categories, sub-categories, locations, and monthly sales targets. The packaged Tableau workbook and source CSV files are included in this repository.

## Objectives

- Analyse sales and profit performance.
- Compare product categories and sub-categories.
- Explore order and geographic performance.
- Compare monthly sales against category-level targets.
- Identify low-profit or loss-making areas for further investigation.

## Tools Used

- Tableau Desktop / Tableau Public
- CSV datasets

## Repository Structure

```text
Retail-Sales-Profitability-Analysis/
├── Retail_Sales_Profitability_Analysis.twbx
├── data/
│   ├── order_details.csv
│   ├── list_of_orders.csv
│   └── sales_target.csv
├── screenshots/
│   └── dashboard.png
├── README.md
└── .gitignore
```

## Dataset Description

| File | Description | Key fields |
|---|---|---|
| `order_details.csv` | Product-level order details | Order ID, Amount, Profit, Quantity, Category, Sub-Category |
| `list_of_orders.csv` | Order dates and customer/location details | Order ID, Order Date, CustomerName, State, City |
| `sales_target.csv` | Monthly targets by category | Month of Order Date, Category, Target |

## How to Open the Workbook

1. Download or clone this repository.
2. Open `Retail_Sales_Profitability_Analysis.twbx` in Tableau Desktop.
3. If Tableau reports a missing data source, edit the connection and point it to the relevant CSV file in the `data/` folder.
4. Review the dashboard, filters, data relationships, and calculations.

> A `.twbx` file is a Tableau Packaged Workbook. Check that its data connections work on your computer before sharing or publishing it.

## Business Questions

- Which categories and sub-categories contribute most to sales?
- Which categories or sub-categories have low or negative profit?
- How does performance vary by state or city?
- How do sales and profit change over time?
- How do monthly sales compare with category-level targets?

## Dashboard Preview

After taking a screenshot of the dashboard, save it as `screenshots/dashboard.png` and display it here:

![Retail Sales & Profitability Analysis Dashboard](screenshots/dashboard.png)

## Skills Demonstrated

- Tableau dashboard development
- Data visualisation and exploratory analysis
- Sales and profitability analysis
- Category and geographic comparisons
- KPI and target tracking
- Data source organisation

## Author

**Siddhartha V. G.**

- GitHub: https://github.com/siddharthhhh725
- Portfolio: https://siddharthhhh725.github.io
- LinkedIn: https://linkedin.com/in/siddharthavv

## Disclaimer

This project is shared for learning and portfolio demonstration. Validate the workbook's data connections, calculations, and findings before using results for business decisions.
