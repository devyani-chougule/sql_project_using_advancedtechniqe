# time-series-sales-analysis
# MySQL Sales Analysis Queries

📊 Dataset
Table: `master.goldfactsales`

Columns assumed:
- `order_date`
- `sales_amount`
- `customer_key`
- `quantity`

📌 Included Queries

1. **Group by Year and Month**
2. **Group by Truncated Month** (using `DATE_FORMAT`)
3. **Group by Truncated Year**

🛠️ Usage
Run the queries in any MySQL environment connected to the appropriate `master.goldfactsales` table.

📁 Files
- `monthly_sales_summary.sql`: Main SQL logic
