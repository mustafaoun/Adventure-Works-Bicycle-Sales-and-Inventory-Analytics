# Adventure Works Bicycle Sales and Inventory Analytics   

This repository contains the **Adventure Works Bicycle Sales and Inventory Analytics Dashboard**, a comprehensive Power BI project developed as part of my Microsoft Power BI Analyst certificate.  

The dashboard analyzes **sales performance, customer behavior, inventory levels, and profitability** for a simulated global bicycle manufacturing and sales company. It blends **historical data with live insights** to support business decisions such as stock optimization, pricing strategies, and sales forecasting.  

---

## Project Overview  

- **Theme**: Bicycle sales and inventory analytics, distinct from general retail (e.g., Superstore), with a focus on manufacturing and supply chain insights.  
- **Objective**: Provide actionable insights through key metrics like total sales, profit margins, inventory turnover, top-selling products, and regional performance, with what-if scenario analysis.  
- **Data Sources**:  
  - **Historical**: AdventureWorks dataset (CSV files, 2015–2017).  
  - **Live Data**: Simulated API (`Live_Data`) for real-time exchange rates (e.g., `rates.USD`).  
- **Output**: A 5–7 page `.pbix` report published to Power BI Service, featuring interactive dashboards.  

---

## Features  

- **Interactivity**: Buttons, bookmarks, What-If parameters.  
- **Visualizations**: KPIs, line charts, maps, matrices, AI-driven insights (Key Influencers).  
- **Calculations**: Advanced DAX (profit, time intelligence, dynamic adjustments).  
- **Deployment**: Scheduled refresh, and alerts in Power BI Service.  

---

## 🛠 Step-by-Step Development  

### 1. Data Preparation  
- Imported and merged `Sales_2015`, `Sales_2016`, `Sales_2017`.  
- Cleaned `OrderDate`, removed duplicates, integrated `Live_Data` via DirectQuery.  
- Created unified **Product Dimension** table.  

### 2. Data Modeling  
- Built **star schema** (Sales fact + Calendar, Customers, Territories, Product Dimension, Live_Data).  
- Added hierarchies (Date, Product).  
- Removed redundancies and optimized relationships.  

### 3. DAX Calculations  
- Key measures:  
  - `Sales Amount`  
  - `Total Profit`  
  - `Profit Margin %`  
  - YTD/PY comparisons  
  - Scenario adjustments (Price Increase %)  
- Validated measures with KPIs and matrices.  

### 4. Visualization & Analysis  
- Pages:  
  1. Executive Summary  
  2. Sales Analysis  
  3. Market Intelligence  
  4. Inventory Management  
  5. Customer Insights  
  6. Documentation  
- Added navigation buttons, bookmarks, custom tooltips, and themes.  

### 5. Deployment  
- Published to Power BI Service.  
- Created dashboards: **Executive View** & **Operations View**.  
- Configured alerts for thresholds.  

---

## Key Insights  

- Accessories = **68% of sales**, avg. profit margin **40%**.  
- Regional profitability varies → suggests **targeted pricing**.  
- Exchange rates (`rates.USD`) impact costs → hedging recommended.  

---

## Skills Demonstrated  

- **Tools**: Power BI, Power Query, DAX, DirectQuery.  
- **Techniques**: Data blending, star schema modeling, advanced DAX, interactive dashboard design, deployment optimization.  
- **Problem-Solving**: Managed single-row live data limitations, performance tuning.  

---
