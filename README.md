#Data Analytics Project

📊 Business KPI Analysis Dashboard – Power BI Project
📁 Project Overview

This project focuses on analyzing key business performance indicators (KPIs) using Power BI. The goal was to design an interactive dashboard that provides insights into sales performance, customer metrics, and category-wise business behavior across different time periods and regions.

The dashboard includes both Business Performance Analysis and Comparison Insights, helping stakeholders track progress toward goals, identify trends, and support data-driven decision-making.

🎯 Objectives
To monitor and evaluate key business KPIs such as Sales, Quantity Sold, Orders, and Customers.  
To visualize monthly and quarterly sales performance.  
To analyze product category contributions and regional sales distribution.  
To identify top customers driving business growth.  
To create a goal vs. actual comparison for performance optimization.

🧩 Tools & Technologies
• Power BI Desktop – Data visualization & dashboard creation  
• Excel / CSV Dataset – Source of raw data  
• DAX (Data Analysis Expressions) – Used for calculated measures and KPIs  
• Power Query Editor – Used for data transformation and cleaning  

🧮 Data Preparation Steps
Data Importing:  
   Imported raw sales data into Power BI from an Excel/CSV file containing orders, quantities, and customer details.

Data Cleaning:  
   - Removed duplicates and null values.  
   - Standardized column names (Sales, Order ID, Product Category, City, etc.).  
   - Converted data types (e.g., date columns, sales amount to currency format).

Data Transformation (Power Query):  
   - Created new calculated columns for Profit, Goal Achievement %, and Month/Quarter extraction.  
   - Merged and appended queries for unified data structure.

Creating Relationships:  
   Established relationships between Orders, Customers, Products, and Regions tables using primary keys.

📊 Dashboard Design & Components
KPI Summary Cards
Displayed key performance metrics with goal comparisons:

| KPI | Actual | Goal | Achievement |
|-----|---------|------|--------------|
| Sales | 139.11K | 98.93K | +40.61% |
| Quantity Sold | 1358 | 1037 | +30.95% |
| Orders | 247 | 186 | +32.8% |
| Customers | 207 | 165 | +25.45% |

These KPIs provide a direct view of current performance versus targets.

Trend Analysis by Month
• Total Sales by Month line chart shows seasonal fluctuations in performance.
• Orders by Month and Quantity Sold by Month area charts highlight operational trends and customer demand cycles.

Gauge Charts – Goal Achievement Overview
Four gauge visuals summarize:
• Total Sales (688.56K of 1.38M goal)
• Quantity Sold (7019 units)
• Orders (1255 total)
• Customers (582 total)

This view gives at-a-glance target completion tracking.

Comparison Dashboard
Focused on understanding product and regional contributions:
• Total Sales by Product Category: Clothing, Furniture, and Electronics lead in total revenue.
• Order Count by Category: Clothing (22.31%) contributes most, followed by Toys and Books.
• Total Sales by City (Map Visualization): Major sales hubs include New York, Los Angeles, Houston, and Chicago.

Top Customers Analysis
A data table lists the Top 100 Customers showing:
• Customer ID  
• Total Quantity Sold  
• Total Sales Value  

For example, Customer ID 175 accounted for sales of 1,907.51 with 24 units, contributing significantly to total business revenue (aggregate of 2,50,591.09).

Quarterly Trend Visualization
A chart illustrates quarter-wise performance changes, identifying Q2 peaks and Q3 dips, useful for quarterly strategy planning.

📈 Key Insights
• Sales exceeded target by over 40%, indicating strong performance.  
• Clothing category contributed the highest to total sales.  
• New York and Los Angeles were top-performing cities.  
• Quarter 2 showed a revenue spike, suggesting high customer engagement.  
• Consistent order growth and rising customer base across the year demonstrate business expansion.

🚀 Outcomes
• Built an easy-to-navigate Power BI dashboard for tracking performance metrics.  
• Presented both time-based and category-based comparisons.  
• Delivered visual clarity to support quick executive decision-making.  
• Encouraged performance benchmarking using goal vs. actual analysis.

📂 Project Structure

``
📁 PowerBIBusinessKPIAnalysis
│
├── 📄 PowerBIProject.pdf       # Complete dashboard screenshots
├── 📊 Dataset.xlsx              # (Sample or anonymized data)
├── 📘 README.md                 # Project overview documentation
└── 📈 Business_KPI.pbix         # Main Power BI dashboard file
``

🧠 Learnings
• Hands-on experience with DAX calculations and Power Query transformations.  
• Understanding of data modeling, relationships, and filter context.  
• Improved ability to communicate data insights through storytelling visuals.

🏁 Conclusion

This Power BI project transforms raw business data into actionable insights, enabling strategic tracking of key business KPIs. Through goal-based comparisons, trend visualizations, and customer analytics, the dashboard provides a full 360° view of business performance.



