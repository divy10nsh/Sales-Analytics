
# Madhav Ecommerce Sales Dashboard (Power BI)

## Overview
This Power BI project analyzes ecommerce sales performance across customers, products, categories, states, and payment methods.

## Dataset Tables
### orders csv
Typical fields used:
- Order ID
- Customer Name
- State
- Order Date

### Details csv
Typical fields used:
- Category
- Sub-Category
- Amount
- Quantity
- Profit
- PaymentMode
- AOV

## KPIs
- Total Sales (Amount)
- Total Quantity Sold
- Total Profit
- Average Order Value (AOV)

## DAX Measures (Recommended Explicit Versions)
```DAX
Total Amount = SUM('Details csv'[Amount])

Total Quantity = SUM('Details csv'[Quantity])

Total Profit = SUM('Details csv'[Profit])

AOV = SUM('Details csv'[AOV])
```

## Visuals
- Sales by Category
- Sales by Sub-Category
- Sales by State
- Sales by Customer
- Payment Mode Analysis
- Profit Analysis

## Insights
- Identify top-performing categories and sub-categories.
- Compare sales performance across states.
- Analyze customer contribution to revenue.
- Evaluate payment method preferences.
- Track profitability and order value trends.

## Files
- newvbi.pbix — Power BI report
- README.md — Project documentation

## Tools Used
- Microsoft Power BI Desktop
- DAX
- Data Modeling
- Data Visualization
# Sales-Analytics
