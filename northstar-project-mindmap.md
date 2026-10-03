# Northstar Retail Sales Analysis — Project Mind Map

```mermaid
mindmap
  root((Northstar Retail Sales Analysis))
    Business objective
      Monitor 2025 sales performance
      Compare actual sales with monthly targets
      Identify performance by region category and channel
      Monitor returns and profitability
    Source data
      Raw Sales
      Products
      Customers
      Monthly Targets
      Data Dictionary
    Data quality
      Remove exact duplicate rows
      Check missing values
      Check negative or invalid values
      Standardize text fields
        Channel Raw to Channel clean
        Store Raw to Store clean
        Payment Method Raw to Payment Method clean
        Customer ID clean
      Parse Customer Info
        Customer name
        Customer city
        Customer segment
    Data enrichment
      Product lookup by Product ID
        Product name
        Category
        Unit cost
      Customer lookup by Customer ID
        Region
    Calculated fields
      Gross Sales
        Unit Price times Quantity
      Discount Amount
        Gross Sales times Discount Pct
      Net Sales
        Gross Sales minus Discount Amount
      Total Cost
        Unit Cost times Quantity
      Profit
        Net Sales minus Total Cost
      Profit Margin
        Profit divided by Net Sales
      Return Flag
        Yes equals 1
        No equals 0
      Date fields
        Year
        Month number
        Month name
        Quarter
        Month start
    Analysis
      Monthly targets
        Actual sales
        Target sales
        Variance
        Achievement rate
      Regional performance
        Net sales by region
        Profit by region
      Returns
        Average Return Flag by category
    Dashboard
      KPI cards
        Net sales
        Total profit
        Total orders
        Target attainment
      Charts
        Monthly net sales trend
        Net sales and profit by region
        Return rate by category
      Slicers
        Channel
        Region
        Category
      Key insights
        British Columbia top region
        Office highest return rate
        January best target attainment
    Validation and publishing
      Reconcile calculated fields
      Check PivotTable totals
      Test slicers
      Save final workbook
      Publish workbook screenshot and README on GitHub
```

## Project outcome

The project transformed raw retail transactions into an Excel dashboard for monitoring sales, profit, targets, returns, and performance drivers.
