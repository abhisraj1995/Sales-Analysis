# Sales-Analysis
# 📊 Sales Analysis Dashboard  
**Period Covered:** Sep 2021 – Dec 2022  

---

## 🧭 Overview  
The **Sales Analysis Dashboard** is an interactive Power BI report designed to track key business metrics such as **Units Sold, Gross Sales, Discounts, Net Sales, Cost of Goods, and Profit**.  
It provides a clear view of sales performance across time periods, territories, and manager segments — empowering decision-makers with actionable insights.  

---

## 🎯 Purpose  
To deliver a **centralized and dynamic reporting tool** that helps business leaders monitor profitability, understand discount impacts, and evaluate sales performance trends across different markets and managers.  

---

## ⚙️ Tech Stack  
| Tool | Purpose |
|------|----------|
| 🧠 **Power BI Desktop** | Main data visualization and reporting platform |
| 🧹 **Power Query** | Data cleaning, shaping, and transformations |
| 🧮 **DAX (Data Analysis Expressions)** | Calculations for KPIs like Profit, Profit Margin %, YOY growth |
| 🗃️ **Data Modeling (Star Schema)** | Connecting dimension tables (Date, Manager) with fact tables (Sales) |
| 💾 **File Formats** | `.pbix` (Power BI project), `.png` (dashboard preview) |

---

## 🗂️ Data Model & Source  
**Source:** Simulated sales dataset created in Excel for analytics demonstration.  

### 📋 Tables Overview  

#### 🧾 FACT_SALES  
Contains transactional data with columns:  
`YearMonth`, `Segment`, `Country`, `Product`, `Discount Band`, `Manager ID`, `Units Sold`, `Sales Price`, `Gross Sales`, `Discounts`, `COGs`, and `Profit`.  
Used to calculate KPIs and performance trends.

#### 👨‍💼 DIM_MANAGERS  
Includes manager details: `Manager ID`, `Name`, `Territory`, and `Image URL` — used for personalized visuals.  

#### 📅 DIM_DATE  
Provides structured time attributes: `Year`, `Month`, `Quarter`, `Reporting Period` — used for time-series analysis.  

#### 🕒 LAST_REFRESHED  
Stores the most recent dataset refresh timestamp (displayed dynamically in the report).  

---

## 🧩 Business Problem  
Sales teams lacked a unified, data-driven view of their performance metrics across managers, countries, and time periods.  
Manual Excel reporting made it difficult to monitor **discount impact**, **profitability**, and **sales performance** efficiently.  

---

## 🚀 Dashboard Goals  
✅ Analyze **sales performance trends** over time  
✅ Measure **discount impact** on profitability  
✅ Compare **regional and manager-wise performance**  
✅ Enable **interactive exploration** with filters and bookmarks  

---

## 📈 Dashboard Walkthrough  

### 🔹 **Top KPIs (Cards)**  
| Metric | Value |
|--------|--------|
| 🧾 **Units Sold** | 1.12M |
| 💰 **Gross Sales** | ₹12.79 Cr |
| 🎟️ **Discounts** | ₹92.05 L |
| 💵 **Net Sales** | ₹11.87 Cr |
| ⚙️ **Cost of Goods** | ₹10.18 Cr |
| 🏆 **Profit** | ₹1.68 Cr |
| 📊 **YOY Growth** | +14% |

---

### 📉 **Trend Visuals (Line Charts)**  
- 📦 **Units Sold by Period** → Tracks monthly sales and seasonality  
- 💸 **Net Sales by Period** → Shows total revenue post discounts  
- 💹 **Profit by Period** → Highlights profitability and YOY growth  
- 🧾 **Cost of Goods by Period** → Evaluates operational cost trends  

---

### 📋 **Detailed Summary Table**  
Breaks down sales by **month**, showing:  
Units Sold, Gross Sales, Discounts, COGs, Profit, and Profit Margin %.  

---

### 🧭 **Sidebar Navigation**  
Interactive vertical menu for quick exploration:  
🏠 Home | 🕓 Period | 🧩 Segment | 🌎 Country | 📦 Product | ❓ Help  

Each page focuses on a unique analytical dimension.  

---

## 💡 Business Impact & Insights  
✨ **Data-Driven Decisions:** Simplified profit and discount tracking.  
📊 **Enhanced Transparency:** Unified dashboard for all managers.  
🚀 **Performance Optimization:** Identified top regions and performers.  
🕒 **Operational Efficiency:** Reduced manual reporting effort.  

---

## 🖼️ Dashboard Preview  
![Sales Analysis Dashboard Preview]([https://github.com/abhisraj1995/Sales-Analysis/blob/main/Sales%20Analysis%20Report%20DashBoard.png] 
*Alt Text: Power BI dashboard showing KPIs, charts, and sales performance (Sep 2021–Dec 2022)* 

---

## 🧠 Key Learnings  
- Designed an intuitive, storytelling layout using bookmarks and page navigation.  
- Built advanced DAX measures for profit & margin analysis.  
- Improved report interactivity using slicers, filters, and buttons.  
- Adopted BI design best practices for clean and professional visuals.  

---

## 🪄 Future Enhancements  
🔹 Add **region-wise drillthrough** pages for deeper insights.  
🔹 Integrate **forecasting visuals** for predictive sales trends.  
🔹 Publish via **Power BI Service** with scheduled refreshes.  

---

## 👨‍💻 Author  
**Abhishek Raj**  
💼 Data Analyst | Power BI Developer + SQL + Excel | Data Enthusiast  
📧 [abhisraj.111995@gmail.com]

---

⭐ *If you found this helpful, consider giving the repo a star!*
