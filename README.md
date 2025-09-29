# 📊 Adventure Works Sales Analysis with Power BI

## Project Overview  
This project showcases an **interactive Power BI dashboard** built using the **Adventure Works 2012 dataset**. The analysis uncovers sales performance, shipping efficiency, product demand, and regional contributions, providing a **360° view of business performance** for decision-making.

The dataset was queried directly from **SQL Server**, transformed in Power BI, and enriched with **DAX measures** for real-time insights.


## Dataset Details  
The dataset used is **AdventureWorks 2012**, a widely used sample database from Microsoft.  
- It contains tables for orders, products, customers, sales, shipping, territory, and more.  
- You can download the database (backup file) from Microsoft’s official documentation:  
  [AdventureWorks sample database download](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver17&tabs=ssms#download-backup-files)  


## 🔑 Key Highlights  
- **SQL Connection** – Queried and extracted data directly from SQL Server.  
- **Data Transformation** – Cleaned and structured data, categorized order statuses, optimized model.  
- **DAX Measures** – Built KPIs: Total Sales, Orders, Tax, Freight, and Order Quantity.  
- **Interactive Visuals** – Drill-down charts, tooltips, decomposition tree, and trend analysis.  
- **Business Insights** – Identified top-selling products, revenue-driving regions, and logistics dependencies.  


##Dashboard Insights  

### 1️⃣ Overall KPIs  
- **Total Orders**: 31K  
- **Total Subtotal**: $109.8M  
- **Total Tax**: $10.2M  
- **Total Freight**: $3.2M  
- **Total Due**: $123.2M  

These metrics give a quick snapshot of business health.


### 2️⃣ Orders by Shipping Method  
- **XRQ – Truck Ground**: 87.9%  
- **Cargo Transport 5**: 12.1%  
➡️ Highlights dependency on a single shipping method.


### 3️⃣ Orders & Total Due by Territory  
- **North America**: Highest orders and revenue.  
- **Europe & Pacific**: Significant contributors.  
➡️ Reveals geographical strengths and weaknesses.


### 4️⃣ Product Analysis  
- Hierarchical breakdown by **Category → Subcategory → Product**.  
- Top demand in **Accessories & Bikes** (e.g., Bib-Shorts, Bike Racks).  
➡️ Identifies best-selling and underperforming products.


### 5️⃣ Orders by Status  
- Majority of orders are **Shipped**.  
➡️ Useful for logistics and order fulfillment analysis.


### 6️⃣ Orders Over Time  
- Trend analysis from **2005 – 2008**.  
- Seasonal spikes and long-term growth observed.  
➡️ Helps with **demand forecasting & inventory planning**.


### 7️⃣ Total Due by Country  
- **Southwest**: Highest total due.  
- **Canada & Northwest**: Strong contributors.  
- **Australia**: $11.81M.  
- **Germany**: Lowest at $5.48M.  
➡️ Supports financial planning and regional performance monitoring.


## Tools & Technologies  
- **Power BI** – Data modeling, DAX, visualizations.  
- **SQL Server / AdventureWorks database** for data extraction.  
- **AdventureWorks 2012 sample dataset**  
- **Visualization Techniques**: KPIs, Pie charts, Line charts, Decomposition tree, Bar charts, Bubble charts.


## Key Takeaways  
- Built an **end-to-end BI solution** for sales performance analysis.  
- Delivered actionable insights into **finance, product demand, shipping efficiency, and regions**.  
- Demonstrated the power of **Power BI** in driving **data-driven decisions**.


## 📷 Dashboard Preview  
<img width="1308" height="731" alt="Screenshot 2025-09-29 192100" src="https://github.com/user-attachments/assets/ca328337-737d-4058-8f3a-0718677089f9" />
