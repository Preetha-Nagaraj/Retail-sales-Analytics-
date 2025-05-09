📊Retail-sales-Analytics

Retail Sales Analytics Using Excel, SQL & Power BI
This project presents a complete Retail Sales Analytics solution using Excel for data cleaning, SQL for querying, and Power BI for visualization. The goal is to enable effective business decision-making in a competitive retail environment by analyzing sales, customer behavior, inventory, and store performance.

📌 Problem Statement
In a highly competitive retail market, businesses need to:

Track sales performance across stores and products

Understand customer buying patterns

Perform segmentation for targeted marketing

Monitor inventory and discounts

🔧 Tools Used
Excel – Data preprocessing & validation

SQL (MySQL/PostgreSQL) – Data storage, transformations, and analysis

Power BI – Visualization and dashboard design

Generate actionable insights using interactive dashboards

🧭 Project Workflow
Phase 1: Excel – Data Cleaning & Preparation
✅ Steps:

->Standardized Column Headers: Ensured consistent naming across all datasets.

->Removed Duplicates: Cleansed customer/order tables for redundant entries.

->Handled Missing Values: Replaced blank ZIPs and phone numbers with "NA".

->Converted Data Types: Dates converted to Date type, numeric fields verified.

->Data Validation: Added dropdowns for order_status to maintain consistency.

->Derived Columns: Created total_price = (list_price * quantity) - discount.

->Lookup Merging: Used VLOOKUP to combine product details into order_items.

->Outlier Detection: Identified extreme values in pricing for correction.

->Pivot Table: Summarized sales by product category.

Datasets 
(customers.csv, orders.csv, etc.) for SQL import.[Retail Sales.xlsx](https://github.com/user-attachments/files/20123951/Retail.Sales.xlsx)

Phase 2: SQL – Database Management & Querying
✅ Steps:

Created Tables: Defined structure using CREATE TABLE with constraints.

Imported Files: Loaded cleaned data into SQL using import tools.

Joins for Order Insights: Merged orders, order_items, and products for detailed views.

📊 Phase 3: Power BI – Dashboard & Visualization
Built an interactive dashboard with the following components:

✅ KPIs:
Total Sales, Discounts, Customers, Cost

Progress toward Sales Target

Sales Comparison: Current Year vs Previous Year

📈 Visuals:
Sales Trend by Month

Revenue by Month & State

Product Category Distribution

Low Stock Products (Gauge)

Discount Trends (Area Chart by Year & Category)

Order Status Over Time

Customer Purchase Breakdown

Store Performance (Map View)

📌 Key Business Insights

🚴 Children Bicycles led sales across categories.

🗓️ Peak revenue observed in April.

📍 States like CA, NY, and TX dominated sales.

📉 Over 321 products flagged as low stock.

🧾 High volume of discounted orders needing review.

👥 Customer segmentation revealed top spenders for focused marketing.

Snap for Retail Analytics and Sales Dashboard

![Image](https://github.com/user-attachments/assets/043b88ed-8764-4db2-86d4-b648c6838f7f)
![Image](https://github.com/user-attachments/assets/33fb2553-f6bd-427e-9a5c-f9022692651f)

✅Recomendations

1.Focus on top-selling products (e.g., Children Bicycles) and reduce investment in low performers.

2.Segment customers by spending (Low/Medium/High) for targeted marketing.

3.Optimize inventory using stock alerts for low-quantity products.

4.Capitalize on seasonal peaks (April, July) with promotions.

5.Enhance store performance by analyzing city/state-wise trends and staff productivity.




🏁 Conclusion
This end-to-end analytics solution showcases how a retail business can transform raw sales data into strategic insights using Excel, SQL, and Power BI. It enables performance tracking, customer targeting, and inventory management with visual ease.

