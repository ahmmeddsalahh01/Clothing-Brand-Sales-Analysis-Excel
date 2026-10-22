# Clothing-Brand-Sales-Analysis-Excel
Excel and Power Pivot dashboard analyzing 3,000 clothing orders across 6 stores: sales by category, product, store, and customer, with insights and recommendations.
# Clothing Brand Sales Performance Analysis

An interactive Excel dashboard built with Power Query, Power Pivot, and DAX that analyzes 3,000 orders from a clothing brand with 6 stores, by category, product, store, region, month, and customer.

## Business question
Which categories, products, stores, and customers drive sales, and where should the brand focus stock and promotions?

## Tools
Excel, Power Query, Power Pivot, DAX, PivotTables, slicers

## Data
Dataset: generated for practice. Four linked tables: sales (3,025 raw rows, 3,000 orders after cleaning), products (50), customers (150), and stores (6). Sales cover 2024 and are shown in EGP.

## Data cleaning
- Removed blank rows, duplicate rows, and rows with errors
- Standardized text capitalization in every column, including categories and payment methods
- Converted prices to numbers
- Validated every primary key: each ID is unique, has no blanks, and matches between tables
  
## Dashboard
Four sheets (Sales & Revenue, Product Performance, Store Performance, Customer Behavior) with 27 PivotTables, 13 charts, and slicers, plus a sheet of insights and recommendations.

## Key findings
Total sales were EGP 622K, with an average order value of about EGP 207.
- **Women (25.1%) and Men (22.3%)** make up about 47% of sales. Kids is lowest at 16.2%.
- **North** brings about 48% of sales, South about 35%, and Delta about 18%.
- **Downtown Cairo** is the weakest store, about 19% below the leader, Luxor Plaza.
- Sales do not depend on one product: the best seller is only 2.9% of revenue.
- Sales peak in July and dip in April and December, a gap of roughly 19%.
- The top 10 customers contribute about 17% of sales.

## Recommendations
1. Prioritize stock and marketing for Women and Men, and test promotions for Kids.
2. Review Downtown Cairo's assortment and staffing.
3. Plan seasonal campaigns for April and December.
4. Launch a loyalty program for top customers.
