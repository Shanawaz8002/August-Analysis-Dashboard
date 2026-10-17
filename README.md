# 👶 Little Twins August Sales Performance & Business Intelligence Analysis

## 🎯 Project Objective
The primary objective of this project is to analyze the August retail sales dataset for **Little Twins Baby Store**. By combining data hygiene, SQL analytics (SSMS), and MS Excel interactive dashboarding, this project delivers actionable financial insights, evaluates inventory velocity, tracks hourly peak footfall, and identifies key customer demographic trends to drive revenue growth.

---

## 📁 Dataset & File Structure
- **Dataset Used:** `LittleTwins_August_Sales.csv` (3,443 cleaned retail records, 0 nulls)
- **Data Standard:** Standardized M-Query financial calculations (`Net Sales = Gross Sales - Discount Amount`)
- **Repository Artifacts:**
  - <a href="https://github.com/Shanawaz8002/August-Analysis-Dashboard/blob/main/LittleTwins_August_Sales.xlsx"> (Clean Data File)
  - <a href="https://github.com/Shanawaz8002/August-Analysis-Dashboard/blob/main/Aug%20Analysis%20Dashboard.png"> (Interactive Excel Dashboard)
  - <a href="https://github.com/Shanawaz8002/August-Analysis-Dashboard/blob/main/LittleTwins_AugSales_SQL.docx"> (Production-grade SQL Analytics Scripts)

---

## 📌 Business Requirements & Key Performance Indicators (KPIs)
The dashboard and analytical queries focus on answering core corporate requirements:

### 1. High-Level KPIs (Top Cards)
- **Total Revenue (Net Sales):** Overall revenue generated after discounts.
- **Average Order Value (AOV):** Average monetary value per bill/checkout.
- **Total Quantity Sold:** Total units of baby products sold.
- **Total Transactions:** Total volume of completed store checkouts.
- **Average Items Per Transaction:** Basket density metric.

### 2. Analytical Visualizations (9 Charts)
- **Daily Sales Trend:** Line chart tracking daily revenue patterns across August.
- **Hourly Footfall / Peak Hours:** Area chart monitoring footfall density from 08:00 AM to 10:00 PM.
- **Sales Contribution by Category (%):** Donut chart showing percentage share per category (*Toys, Diapers, Baby Care, Clothing, etc.*).
- **Quantity Sold by Category:** Bar chart displaying unit sales across categories.
- **Top 5 Best Sellers:** High-velocity inventory generating maximum volume.
- **Inventory Slow Movers (Bottom 5):** Underperforming items flagged for clearance bundling.
- **Payment Mode Distribution:** Breakdown across *Debit Card, Swipe Machine, Cash, and Online*.
- **Customer Location Regional Sales:** Sales distribution across store hubs (*Gachibowli, Kukatpally, Shamshabad, Attapur, etc.*).
- **Gender & Age Demographics:** Age brackets and buyer gender distribution split.

---

## 🛠️ Execution Pipeline & Data Process

### Step 1: Data Cleansing & Transformation
- Filtered out corrupt/incomplete rows (reducing messy 3,500 rows to 3,443 clean records).
- Resolved mixed date formats (`YYYY-MM-DD`, `DD-MM-YYYY`, `DD.MM.YYYY`) into a single uniform date format (`DD-MM-YYYY`).
- Re-calculated financial logic (`Gross Sales`, `Discount Amount`, `Net Sales`) using M-Query in Power Query.

### Step 2: SQL Server (SSMS) Analytics
- Ingested clean data into SQL Server Database Engine.
- Authored queries utilizing `GROUP BY`, `DATEPART`, `COUNT(DISTINCT)`, and window functions to compute core KPIs and hourly/daily trends.

### Step 3: Interactive Excel Dashboard Creation
- Built dynamic PivotTables linked directly to clean data model.
- Designed a dark-mode corporate dashboard theme featuring Teal and Orange accent highlights.
- Implemented **4 Interactive Slicers/Filters:** *Date Range Timeline, Category Slicer, Payment Mode Slicer, and Salesperson Filter*.
- Configured interactive hyperlinks on brand assets (Instagram page & Google Maps store location).

---

## 📊 Interactive Dashboard Preview
! [Dashboard Screenshot](https://github.com/Shanawaz8002/August-Analysis-Dashboard/blob/main/Aug%20Analysis%20Dashboard.png)

---

## 💡 Key Business Insights
- **Top Performing Categories:** Toys, Baby Care, and Baby Clothing accounted for the highest volume of total units sold.
- **Operational Peak Windows:** Store footfall peaks consistently during late evening hours (around 7:00 PM - 9:00 PM), requiring optimal staffing.
- **Inventory Velocity:** Products like *MamyPoko Pants* and *Baby Rompers* maintained top seller rankings, while slow-moving items like *Baby Sandals* and *Rattles* showed lower rotation.

---

## 🏁 Final Recommendations
1. **Stock Optimization:** Maintain higher buffer stock for top 5 fast-moving items to prevent stockouts during weekend rush hours.
2. **Promotional Bundling:** Package underperforming slow movers (*Bottom 5 items*) with high-demand categories (*Toys/Diapers*) at a slight bundle discount to accelerate inventory turnover.
3. **Staffing Allocation:** Align salesperson shifts with peak footfall hours (6:00 PM - 9:00 PM) to ensure smooth checkout flow and improve customer satisfaction.

---

### 👨‍💻 Author & Project Maintainer
**Shahnawaz Khan**  
*Data Analytics & Fin Tech Student*  
- **GitHub:** [Shanawaz8002](https://github.com/Shanawaz8002)  
- **LinkedIn:** [Shanawaz Khan](https://www.linkedin.com/in/shahnawaz-khan-b37bba26a)
