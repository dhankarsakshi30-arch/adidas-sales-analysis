# Adidas Sales Analysis Dashboard | Power BI

An interactive Power BI dashboard for exploring Adidas sales performance across time, regions, products, and retailers.

![Adidas Sales Analysis Dashboard](dashboard-preview.jpeg)

## Project Overview

This project presents a sales-performance dashboard built in Microsoft Power BI. It brings key business metrics and several breakdowns into one view to help users explore sales trends and compare performance across regions, product categories, and retail partners.

> **Note:** The figures below are transcribed from the dashboard screenshot. They describe the displayed report and have not been independently validated against the underlying dataset.

## Key Performance Indicators

| KPI | Value shown | What it represents |
|---|---:|---|
| Total Sales | **$666M** | Total sales value displayed in the report |
| Operating Profit | **$243M** | Operating profit displayed in the report |
| Units Sold | **2M** | Total units sold displayed in the report |
| Price per Unit | **$310K** | The visual is labeled “Sum of Price per Unit”; confirm the aggregation and formatting in Power BI before interpreting this as a business KPI |
| Operating Margin | **42%** | Average operating margin displayed in the report |

## Dashboard Sections

### 1. Total Sales by Month
A monthly trend chart showing how sales change throughout the year. In the screenshot, sales rise through the middle of the year, peak around July–August, and fall sharply from September onward.

### 2. Total Sales by State
A map visual intended to show the geographic distribution of sales by state. The screenshot is zoomed out to a world map, so state-level detail is not legible in the preview.

### 3. Total Sales by Region
A doughnut chart comparing sales across five regions:
- West
- Southeast
- Northeast
- Midwest
- South

### 4. Total Sales by Product
A horizontal bar chart ranking product groups by sales. The visible labels include men's and women's apparel and athletic product groups.

### 5. Total Sales by Retailer
A horizontal bar chart comparing retailer sales. Visible retailers include West Gear, Foot Locker, Sports Direct, Kohl's, Walmart, and Amazon.

## Filters and Interactivity

The screenshot shows:
- A **Region** dropdown filter
- An **Invoice Date** date-range filter

These controls allow users to narrow the report to a region or date range, assuming the original Power BI report has the interactions configured.

## Tools

- **Microsoft Power BI** — dashboard design and data visualization
- **GitHub** — project documentation and version control

Add other tools here if you used them (for example, Excel, SQL, or Python).

## Repository Contents

```text
adidas-sales-analysis/
├── README.md
├── dashboard-preview.jpeg
└── Adidas-Sales-Analysis.pbix   # optional: add your Power BI file
```

The `.pbix` file is optional, but include it if you want visitors to inspect or interact with the report in Power BI Desktop. Only add files you have permission to share.

## How to View the Project

1. Open `dashboard-preview.jpeg` in this repository to see the dashboard screenshot.
2. If the `.pbix` file is included, download it.
3. Open the `.pbix` file using **Microsoft Power BI Desktop**.
4. If Power BI asks for a data source or credentials, reconnect the data source using your own authorized access.

A screenshot is a static preview; it does not preserve Power BI filters, tooltips, or interactivity.

## Insights to Explore

Based on the visuals shown, a viewer can investigate:
- How sales vary month by month and which months contribute most to total sales.
- Which regions contribute the largest share of sales.
- Which product groups lead in sales.
- How retailer performance compares.
- Whether regional and date filters change the rankings or sales trend.

Avoid treating these as final business conclusions until you verify the source data, definitions, and report calculations.

## Data and Metric Notes

- The screenshot shows an invoice-date filter from **January 29, 2020 to September 13, 2021**.
- The monthly chart displays January through December; confirm the date grouping and filter context in the original report before drawing conclusions about the exact period.
- The card “Sum of Price per Unit” displays **$310K**. Summing unit prices may not be a meaningful average selling price; consider using a correctly defined average or weighted average if that better matches the project objective.
- Confirm whether the sales and profit figures are in USD and document the source dataset, refresh date, and any data-cleaning steps if known.

## Suggested GitHub Repository Details

- **Repository name:** `adidas-sales-analysis`
- **Short description:** `Power BI dashboard analyzing Adidas sales, profit, units sold, regional performance, products, and retailers.`
- **Topics:** `power-bi`, `data-analytics`, `sales-analysis`, `data-visualization`, `business-intelligence`, `dashboard`
- **Visibility:** Public if you want to showcase it in a portfolio and are allowed to share all included files; otherwise choose Private.

## Future Improvements

- Add the original `.pbix` file if it can be shared.
- Document the dataset source and data dictionary.
- Add definitions for each KPI and explain any DAX measures.
- Check the “Price per Unit” aggregation and currency formatting.
- Improve the map zoom so the relevant geography is visible.
- Add a short section with verified findings after checking the underlying data.
  
