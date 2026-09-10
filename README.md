# CodeAlpha Task 1 – Financial Health Dashboard

## Project Overview

This project is part of my CodeAlpha Power BI Internship – Task 1.

The objective is to develop an interactive Financial Health Dashboard that provides a clear overview of an organization's financial performance and supports financial planning and decision-making.

## Objective

Develop a Power BI dashboard to analyze an organization's financial status and provide dynamic insights useful for small and medium-sized enterprises (SMEs).

## Key Features

- Income Statement analysis
- Balance Sheet analysis
- Cash Flow analysis
- Profitability trends over time
- Revenue forecasting
- Actual vs Budget comparison
- Interactive date filtering
- KPI cards for important financial metrics

## Dashboard Sections

### KPI Cards
- Revenue
- COGS
- Operating Expenses
- Total Profit
- Profit Margin %

### Income Statement
Displays Revenue, COGS, Operating Expenses, and Total Profit.

### Balance Sheet
Displays Assets, Liabilities, and Equity.

### Cash Flow
Displays Cash Inflow and Cash Outflow.

### Profitability Trend
Shows monthly Total Profit trends from January to December 2026.

### Revenue Forecast
Shows historical revenue performance and forecasted revenue.

### Actual vs Budget
Compares actual revenue with budgeted revenue.

## Tools & Technologies

- Microsoft Power BI
- Microsoft Excel
- Power Query
- DAX

## Dataset

The dataset contains monthly financial information for January 2026 to December 2026.

Columns include:

- Date
- Revenue
- COGS
- Operating Expenses
- Assets
- Liabilities
- Equity
- Cash Inflow
- Cash Outflow
- Budget Revenue

## DAX Measures

### Total Profit

```DAX
Total Profit =
SUM(Sheet1[Revenue])
- SUM(Sheet1[COGS])
- SUM(Sheet1[Operating Expenses])
