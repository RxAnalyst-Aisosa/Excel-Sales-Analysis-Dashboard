# Excel Sales Analysis Dashboard

> **Excel portfolio project | Sales performance | KPI analysis | PivotTables | PivotCharts | Slicers**

An interactive Microsoft Excel project that converts **2,098 transactional sales records** into a decision-focused dashboard for monitoring revenue, cost, profit, product performance, sales-representative performance, geographic cost patterns and monthly trends.

![Actual Excel Dashboard](assets/dashboard-preview.webp)

## Executive Summary

The dashboard provides a compact view of business performance and allows users to move from headline KPIs to more detailed operational questions.

| KPI | Dashboard Result |
|---|---:|
| Total Revenue | **£2.328B** |
| Total COGS | **£1.863B** |
| Total Profit | **£465.674M** |
| Profit Margin | **20.0%** |
| Customer Count | **121** |

### Key Findings

- **Peter** generated the highest revenue among the sales representatives shown: **£434.805M**.
- **Laptop A13** was the highest-profit product in the product analysis: **£105.336M**.
- **Lagos** recorded the highest COGS among the cities analysed: **£493.812M**.
- **March** produced the highest monthly profit: **£126.688M**.
- The dashboard reports an overall **20% profit margin**.

## Business Questions

The analysis was designed to answer:

1. What are the business's total revenue, COGS and profit?
2. What is the overall profit margin?
3. Which products contribute the most profit?
4. Which sales representatives generate the most revenue?
5. How does COGS vary by city?
6. How does profit change across months?

## Analytical Approach

The project follows a simple end-to-end Excel workflow:

**Transactional data → structured analysis → KPI calculations → PivotTables → PivotCharts → interactive dashboard → business insights**

The workbook uses Excel-based analysis to summarise performance across products, sales representatives, cities and months. Slicers make the dashboard interactive and allow users to explore different views without changing the underlying analysis.

For a more detailed walkthrough, see **[Project Methodology](docs/METHODOLOGY.md)**.

## Dataset

The source table contains **2,098 records** and 16 fields covering:

- transaction date
- sales representative
- product and category
- quantity
- unit price and cost price
- customer type
- region and city
- sales channel
- revenue
- COGS
- profit
- month index and month label

See the full **[Data Dictionary](docs/DATA_DICTIONARY.md)**.

## Workbook Structure

### 1. `Sales Data`
The underlying transactional dataset used for the analysis.

### 2. `Analysis`
Contains KPI summaries and PivotTable outputs for:

- Product by Profit
- Sales Representative by Revenue
- City by COGS
- Profit by Month

### 3. `Dashboard`
The final interactive reporting layer, combining KPI cards, charts and slicers.

## Dashboard Features

- KPI cards for headline performance
- Product profitability analysis
- Revenue comparison by sales representative
- COGS comparison by city
- Monthly profit analysis
- Interactive slicers
- Clear separation of raw data, analysis and dashboard layers

## Skills Demonstrated

- Microsoft Excel
- Data preparation and structuring
- Excel Tables
- PivotTables
- PivotCharts
- Slicers
- KPI development
- Business performance analysis
- Dashboard design
- Data visualisation
- Insight communication

## Project Files

| File | Purpose |
|---|---|
| **[Excel_Sales_Analysis_Dashboard.xlsx](Excel_Sales_Analysis_Dashboard.xlsx)** | Complete interactive Excel workbook |
| **[analysis-summary.csv](analysis-summary.csv)** | Quick reference for headline KPIs and findings |
| **[Dashboard Preview](assets/dashboard-preview.webp)** | Actual dashboard rendered from the Excel workbook |
| **[METHODOLOGY.md](docs/METHODOLOGY.md)** | Analytical workflow and business questions |
| **[DATA_DICTIONARY.md](docs/DATA_DICTIONARY.md)** | Field definitions and core measures |

## How to Explore the Project

1. Download **[Excel_Sales_Analysis_Dashboard.xlsx](Excel_Sales_Analysis_Dashboard.xlsx)**.
2. Open the workbook in Microsoft Excel.
3. Start with the **Dashboard** sheet for the visual overview.
4. Use the slicers to explore the dashboard interactively.
5. Review the **Analysis** sheet to see the supporting PivotTable summaries.
6. Review **Sales Data** to understand the underlying transactional records.

## Project Context

This project was completed as part of my practical data analytics development with **TS Academy**. The aim was to demonstrate the ability to move from transactional data to an interactive business dashboard and communicate meaningful findings clearly.

---

**Elizabeth Erhunmwunsee**  
*Data Analysis | Excel | Business Intelligence*
