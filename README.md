# Retail Sales Analysis
## Project Overview
A junior-analyst style project analyzing retail transaction data — inspecting, cleaning,
analyzing, and visualizing sales performance.

## Dataset
100 raw transaction records (TransactionID, Date, Country, Product, Quantity, UnitPrice),
cleaned down to 85 valid rows.

## Tools Used
Python, pandas, matplotlib, numpy, Google Colab, Git/GitHub

## Data Cleaning
- Standardized inconsistent text casing/spacing in Country and Product
- Filled missing UnitPrice using average price per product
- Filled missing Country with "Unknown"
- Removed 15 duplicate rows
- Converted Date to datetime, added Year/Month/Day and Revenue columns

## Analysis Performed
- Total revenue, average transaction value
- Top products and countries by revenue
- Products by quantity sold
- Monthly revenue trend
- Quantity-vs-revenue relationship (high quantity does not always mean high revenue)
- Top customers by revenue (simulated CustomerIDs, since none existed in source data)

## Key Findings
1. Total revenue: $12,203.12
2. Bluetooth Speaker is the top product by both revenue and quantity sold
3. USB-C Cable sells in high volume but earns the least revenue — value is not the same as volume
4. Spain is the strongest market, well ahead of other countries
5. February had the highest monthly revenue of the period

## Recommendations
1. Prioritize Bluetooth Speaker in stock and marketing — it drives the most revenue
2. Investigate why Spain outperforms other markets and apply learnings elsewhere
3. Fix the data-collection gap causing missing Country values at the source

## Visualizations
See the `images/` folder: revenue trend (line chart), product and country revenue
(bar charts), transaction value distribution (histogram), quantity vs revenue (scatter plot).

## How to Run the Project
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open `notebooks/` and run the notebook top to bottom
