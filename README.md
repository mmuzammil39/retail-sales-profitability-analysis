# Retail Sales & Profitability Analysis

An end-to-end analysis of retail sales data: cleaning in Excel, analysis in MySQL, and an interactive Power BI dashboard that shows where the business earns money and where discounts hurt profit.

![Dashboard](dashboard.png)

## Business Questions
- How much did the business sell, and how much profit did it make?
- Which product categories, regions, and customer segments drive sales and profit?
- How do sales change month to month?
- Is the average discount affecting profitability?

## Tools Used
Excel (cleaning and validation) | MySQL (analysis) | Power BI (dashboard and KPIs)

## Key Numbers
| KPI | Value |
|---|---|
| Total Sales | 916.04K |
| Total Profit | 23.86K |
| Quantity Sold | 8K |
| Average Discount | 21.72% |
| Profit Margin (Profit / Sales) | about 2.6% |

**Sales by customer segment:** Consumer 331.84K (36.23%) | Corporate 301.19K (32.88%) | Home Office 283.01K (30.89%)

## Key Insights
- Profit is only about 2.6% of sales while the average discount is 21.72%, so heavy discounting is a likely drag on margin.
- Sales are spread fairly evenly across the three customer segments; no single segment dominates.
- [TODO: add your findings: best and worst category by profit, strongest and weakest region, peak sales months]

## Project Workflow
1. **Clean and validate (Excel):** [TODO: list what you fixed, e.g. duplicates, missing values, date formats]
2. **Analyze (MySQL):** queries on sales, profit, category, customer segment, and region. See `sql/`.
3. **Visualize (Power BI):** KPI cards, sales by category, profit by region, monthly sales trend, sales by segment, and a region slicer.

## Repository Structure
```
retail-sales-profitability-analysis/
|-- data/            # dataset or link to its source
|-- sql/             # MySQL queries
|-- dashboard/       # Retail_Sales_Dashboard.pbix
|-- screenshots/     # dashboard images
`-- README.md
```

## Dataset
[TODO: dataset name and link to the source]

## How to Open
Download `Retail_Sales_Dashboard.pbix` from `dashboard/` and open it in Power BI Desktop.

## Author
Mohammed Muzammil | [LinkedIn](https://linkedin.com/in/mmuzammil39) | muzammilmohammad330@gmail.com
