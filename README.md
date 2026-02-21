# 📊 Sales Performance Dashboard (Power BI)

## 📌 Project Overview

This project presents an interactive **Sales Performance Dashboard** built using Power BI to analyze company sales, profitability, shipment trends, and salesperson performance across multiple regions.

The dashboard helps business stakeholders monitor KPIs, identify high-performing products and salespersons, and improve profit margins through data-driven insights.

---

## 🎯 Business Problem

The company needs a centralized dashboard to:

- Monitor overall sales and profitability
- Track shipment performance
- Compare salesperson contributions
- Identify cost-heavy regions
- Improve operational efficiency

Manual Excel analysis was time-consuming and lacked dynamic filtering.

---

## 🚀 Solution

Developed an interactive Power BI dashboard featuring:

- KPI summary cards
- Country-level filters
- Monthly sales trend analysis
- Shipment performance visualization
- Product-wise and salesperson-wise breakdown
- Profit % and LBS% performance metrics

---

## 📈 Key KPIs Tracked

- 💰 Total Sales: $34M  
- 📦 Total Boxes: 2M  
- 🚚 Total Shipments: 6K  
- 💵 Total Cost: $14M  
- 📊 Total Profit: $21M  

---

## 🗂 Data Model

The project follows a structured data modeling approach:

- **Fact Table:** Shipments
- **Dimension Tables:** Calendar, Locations, People, Products
- **Measures Table:** Dedicated DAX measures for calculations
- Implemented star schema modeling principles

---

## 🧮 DAX Measures Used

- Total Sales
- Total Cost
- Total Profit
- Profit %
- LBS %
- Dynamic Measure Selector
- Time-based calculations using Calendar table

---

## 📊 Dashboard Features

- Interactive slicers (Country filter)
- Line charts for trend analysis
- KPI cards for executive summary
- Conditional formatting in performance tables
- Shipment distribution analysis
- Drill-down capability

---

## 📷 Dashboard Preview

![Dashboard Preview](dashboard_preview.png)

---

## 🔍 Key Insights

- Top-performing salespersons contribute significantly to total revenue.
- Profit margins average around 58%.
- Certain regions show higher cost fluctuations.
- Shipment trends indicate seasonal variation.
- A small group of products drive majority of profits.

---

## 🛠 Tools & Technologies Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Excel Dataset
- Data Modeling (Star Schema)
- Data Visualization Techniques

---

## 📁 Repository Contents

- `Sales_Performance_Dashboard.pbix`
- `ac-sample-data.xlsx`
- `dashboard_preview.png`

---

## 👤 Author

Venkatananda Ganesh Manne  
Aspiring Data Analyst | Power BI Enthusiast  

---

## 📌 Future Improvements

- Add forecasting using time intelligence
- Integrate SQL-based data source
- Deploy dashboard to Power BI Service
- Add row-level security implementation
