# Vendor-Performance-Analysis-python-powerbi

This project performs a detailed **Vendor Performance Analysis** by consolidating multiple SQL data sources, analyzing performance metrics, and visualizing key business insights in Power BI. The objective is to help decision-makers identify underperforming vendors, optimize procurement strategies, and enhance vendor management.


## 📌  Objective
Designed and developed a complete data analytics solution to assess vendor performance by automating the extraction, processing, and visualization of multi-source transactional data. The project aims to support procurement teams in identifying underperforming vendors, optimizing pricing and promotional strategies, and improving inventory and supplier management.

🛠️ Tools & Technologies
Python 3.x – Data processing and automation

Pandas – Data manipulation and feature engineering

SQLite3 – SQL querying of structured relational data

Power BI – Interactive and dynamic business intelligence dashboards

Matplotlib / Seaborn – Optional visual exploration during EDA

Logging – Error handling and process traceability

📂 Project Workflow
1. 🔄 Data Ingestion & Transformation
Developed Python script (get_vendor_summary.py) to connect to multiple relational tables.

Consolidated product, purchase, sales, and vendor master data into a unified analysis-ready dataset.

Handled missing values, ensured schema consistency, and applied business-specific transformations.

2. 📊 Exploratory Data Analysis (EDA)
Conducted preliminary analysis to detect null values, duplicates, and outliers.

Grouped vendors and brands by performance KPIs such as sales volume, profit margins, and inventory movement.

Generated summary statistics and category-level trends to support modeling and business decisions.

3. 📈 Vendor Performance Evaluation
Key business questions addressed:

Which vendors and brands exhibit strong sales performance and profitability?

Which suppliers contribute the highest to total procurement value?

How dependent is the business on top-tier vendors?

Are there vendors locking up capital in slow-moving or unsold inventory?

Can bulk purchasing reduce unit costs and what is the optimal purchase volume for savings?

Which vendors require price or promotional adjustments to optimize performance?

📊 Power BI Dashboard Highlights
KPI cards displaying total procurement, vendor count, and unsold inventory.

Bar and line charts visualizing vendor contribution, unit pricing trends, and profit margins.

Slicers to filter insights by brand, category, or vendor segment.

Drill-down reports to identify high-performing and low-performing vendors at a glance.

✅ Impact & Takeaways
Delivered a reusable, scalable, and automation-ready analytics pipeline.

Enabled data-driven decision-making in procurement and vendor selection.

Enhanced visibility into operational bottlenecks such as cost inefficiencies and inventory lock-up.

Demonstrated proficiency across the full data workflow: SQL querying → Python transformation → BI reporting.


![image](https://github.com/user-attachments/assets/07a32b68-783a-4a5a-abd8-19811b13974a)

![image](https://github.com/user-attachments/assets/ed666aa2-e286-442e-93f3-b567e1f03bf8)
