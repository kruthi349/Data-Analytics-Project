# Coffee Shop Sales Data Analysis

This project analyzes sales data from a coffee shop using Excel, Python, and Power BI.  
The dataset was already clean, so minimal preprocessing was needed — only minor modifications for analysis (e.g., adding calculated fields).

## Dataset
- Source: Coffee Shop Transactions (provided as Excel file)
- Fields:
  - `transaction_id`
  - `transaction_date`
  - `transaction_time`
  - `transaction_qty`
  - `store_id`
  - `store_location`
  - `product_id`
  - `unit_price`
  - `product_category`
  - `product_type`
  - `product_detail`
  - Calculated: `Total Sales` = `transaction_qty * unit_price`

## Excel Analysis
- Created PivotTables for Bar & Pie Charts and created a dashboard

## Python EDA & Visualization
- Tools: pandas, matplotlib, seaborn
- Steps:
  1. Loaded the dataset from Excel.
  2. Added `Total Sales` column.
  3. Extracted time-based features (Month, Day of Week, Hour).
  4. Visualizations:
     - Top Sales by Month
     - Sales by Category
     - Top 10 Products
     - Sales by Store Location

## Power BI Dashboard
- Imported dataset and set up relationships.
- Created measures:
  - Total Sales = `SUMX(Sheet, transaction_qty * unit_price)`
  - Total Transactions
  - Average Order Value
- Visuals:
  - Sales Trend by Date
  - Sales by Product Category
  - Top 10 Best-Selling Products
  - Sales by Store Location
- Added filters for Store, Category, and Date.
  
## Key Insights
- Identified best-selling products and categories.
- Found peak sales days 
- Compared store performance across locations.



