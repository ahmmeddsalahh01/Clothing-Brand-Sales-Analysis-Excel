# Clothing Brand Sales Analytics

## Small overview

An interactive Excel dashboard project analyzing sales, products, stores, and customers for a clothing brand. It combines source tables and an Excel Data Model with pivot-based dashboards and recommendations. The workbook reports sales in Egyptian pounds (EGP). The dataset is generated practice data, including fictional customer details.

## Business questions

 How do sales and order volume change by month?
 Which product categories and products contribute most to sales and units sold?
 Which stores and regions generate the highest sales and order volume?
 What do customers buy, how much do they spend, and which payment methods do they use?
 Where are the largest opportunities to improve sales, operations, or data quality?

## Data

The project folder contains:

 `Brand Sales Project.xlsx`  Excel Data Model, pivot-based dashboard pages, supporting analysis, and written insights and recommendations
 `clothing_brand_sales_raw.xlsx`  source workbook with four tables:
 `Sales_Data_Raw`  3,025 transaction-line records with order ID, date, customer, product, store, quantity, unit price, and payment method
 `Product_List_Raw`  56 product records with product name, category, brand, and price
 `Customer_List_Raw`  155 fictional customer records with name, email, phone, city, and signup date
 `Store_List_Raw`  7 store records with store name, city, and region
 `Dashboard Screenshots/`  exported images of the four dashboard pages

The workbook's Data Model relates sales to products, customers, stores, and a calendar table. The dashboards show 3,000 orders, 150 customers, 50 products, and six stores with sales; records in the source lists may include items with no matching sales.

**Practice-data note:** The customer names, email addresses, and phone numbers in the raw workbook are fictional generated records, not real customer contact details.

## Dashboard pages

1. **Sales & Revenue**  total sales, quantity sold, average order value, monthly sales, sales by store, category, and region; includes brand and month slicers.
2. **Product Performance**  product count, category contribution, top products by sales, and top products by quantity.
3. **Store Performance**  total sales and quantity, store sales ranking, and order count by store; includes month and brand slicers.
4. **Customer Behavior**  sales and orders per customer, top customers, payment method mix, customer purchase quantities, and sales by city.
5. **Key insights and Recommendation**  written summary of findings and proposed actions.
6. **Analytics Engine**  supporting pivot tables and calculations for the dashboard views.

## Detailed key findings

- The Sales & Revenue dashboard reports **622,246 EGP** in sales, **12,926 units** sold, and an **average order value of 207 EGP**. The supporting pivot table gives a more precise average of about **207.42 EGP per order** across **3,000 orders**.
- Monthly sales range from about **46,207 EGP in April** to **57,190 EGP in July**. May (**56,334 EGP**) and February (**55,696 EGP**) are also among the stronger months. The pivot table contains **773.84 EGP** under a blank month category.
- Women is the largest category by sales at **156,357 EGP (25.13%)**, followed by Men at **138,758 EGP (22.30%)**. Kids is the smallest category at **100,610 EGP (16.17%)**. Accessories contribute **18.75%** and Shoes **17.66%**.
- Sneakers 1 is the leading product by sales at about **18,084 EGP**, roughly **2.9%** of total sales. Dress 2 leads the displayed top products by units, with **358 units**. Sales are spread across many products rather than dominated by one item.
- Luxor Plaza has the highest store sales at about **114,472 EGP**, followed by Mansoura Center at **110,337 EGP**. Downtown Cairo is lowest at about **93,166 EGP**, around **18.6% below** Luxor Plaza.
- North contributes about **296,281 EGP (47.6%)** of sales, South about **215,627 EGP (34.7%)**, and Delta about **110,337 EGP (17.7%)**. Delta's total is from the Mansoura Center store in the supplied dashboard data.
- Cash (**212,253 EGP**) and Credit Card (**209,202 EGP**) are the largest payment categories, each contributing about **34%**. Mobile Wallet accounts for about **21.5%**; **67,053 EGP (10.8%)** is categorized as “Not Mentioned.”
- The dashboard reports **150 customers** and **3,000 orders**, or **20 orders per customer** as an overall ratio. The top ten customers contribute about **103,301 EGP**, or **16.6%** of total sales. Khaled Hassan is highest among them at about **12,915 EGP**.
- The dashboard shows six stores with sales, while the source store list has seven records; it shows 50 products while the source product list has 56 records. These differences may mean some catalog entries had no sales, but unmatched IDs should be checked before assuming that.
- The written insights sheet contains store-order figures that differ from the supporting pivot tables and dashboard: it cites 473 orders for Downtown Cairo and 530 for Mansoura Center, while the dashboard shows 470 and 525. The narrative should be updated to match the current workbook.

## Advanced recommendations

1. **Prioritize stock for the strongest categories.** Women and Men together contribute about 47.4% of sales. Protect availability for their reliable sellers, but base any range expansion on gross margin, sell-through, and stockout data—not revenue share alone. Keep testing the Kids category rather than cutting it automatically; use a limited assortment or targeted promotion and compare the resulting sell-through and profit.
2. **Protect key products and test bundles.** Maintain sensible safety stock for Sneakers 1, the leading product by sales, and Dress 2, the leading item in the displayed top products by units. Test bundles that pair these products with slower-moving complementary items. Keep a bundle only if it increases units per order and gross profit without simply discounting purchases that would have happened anyway.
3. **Launch a focused Downtown Cairo recovery plan.** Downtown Cairo has the lowest sales and order count in the current dashboard. Have the store manager review availability of top products, size gaps, footfall, conversion, local promotions, and staffing coverage. Test one change at a time, then compare sales per visitor, conversion, and gross margin with the store's own baseline and comparable stores before changing the store's long-term plan.
4. **Use slow-month promotions with a profit guardrail.** April and December are the lowest-sales months in the displayed year. Plan limited, targeted offers or local campaigns for these periods, prioritizing products with healthy margins or excess stock. Compare incremental gross profit and sell-through with a normal-period baseline; avoid treating one year's pattern as a permanent seasonal trend.
5. **Build repeat purchases among high-value customers.** The top ten customers contribute about 16.6% of sales. Offer relevant early access, replenishment reminders, or loyalty benefits to repeat customers, and use product preferences to personalize recommendations. Track repeat-purchase rate, retention, and gross profit per customer so rewards do not erode margin.
6. **Grow mobile-wallet use and improve checkout records.** Mobile Wallet already represents about 21.5% of sales, while 10.8% is categorized as “Not Mentioned.” Make mobile wallet easy to choose and test a small, time-limited incentive only if its incremental profit exceeds its cost. Train staff and validate checkout steps so every transaction receives a consistent payment-method value.
7. **Use the store leaders as operational benchmarks.** Compare practices at Luxor Plaza and Mansoura Center with Downtown Cairo, adjusting for footfall, operating days, store size, and local inventory. Delta's sales come from one store in this dataset, so treat expansion there as a hypothesis; assess rent, demand, and profitability in a small pilot before committing to another location.
8. **Set a monthly action review.** Review sales, orders, units, average order value, gross margin, stockouts, and returns by category and store. Assign an owner and a target to each initiative, then continue, adjust, or stop it based on measured results.

## Tools
 Microsoft Excel (`.xlsx` source workbook)
