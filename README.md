# Awesome Chocolates – Power BI Data Analysis

## Business Problem

Awesome Chocolates operates across multiple countries with a wide product portfolio and a growing sales team. Management needed a **single, interactive view** to answer key questions:

* How are **sales, cost, profit, and shipments** performing month-over-month?
* Which **countries and regions** contribute the most to revenue and profit?
* How efficient is the **sales force** in terms of profit margin and shipment weight (LBS %)?
* Where are **cost fluctuations** happening during the month?

The challenge was to transform raw transactional data into **clear, decision-ready insights** that leadership could use to improve profitability and operational efficiency.

---

## Tools Used

* **Power BI Desktop** – Data modeling, DAX calculations, and dashboard creation
* **Power Query** – Data cleaning, transformation, and shaping
* **DAX (Data Analysis Expressions)** – Measures for KPIs such as Total Sales, Profit %, MoM Growth, and LBS %
* **Excel / CSV (Source Data)**

---

## Steps Performed

1. **Data Import & Cleaning**

   * Imported raw data into Power BI
   * Removed duplicates and handled missing values
   * Standardized country and product names

2. **Data Modeling**

   * Built a star schema for optimal performance
   * Created relationships between tables

3. **DAX Calculations**

   * Total Sales, Total Cost, Total Profit
   * Profit % and LBS %
   * Month-over-Month (MoM) growth
   * Shipment counts and box totals

4. **Dashboard Design**

   * KPI cards for Sales, Cost, Profit, Shipments, and Boxes
   * Line chart for cost trends by start of month
   * Bar chart for shipment analysis
   * Donut chart for country-wise contribution as Tooltip
   * Salesperson and Product tables with conditional formatting (Bookmarks)

5. **Interactivity**

   * Slicers for country, product category, and time
   * Drill-down and cross-filtering across visuals

---

## Key Learnings

* **Profitability varies more by region than by total sales volume**, highlighting the importance of margin analysis
* Certain countries contribute **moderate sales but high profit %**, making them strategic focus areas
* Salesperson-level analysis revealed **clear top performers** based on profit efficiency, not just revenue
* Visual KPIs significantly reduce the time needed for stakeholders to identify trends and issues

---

## Screenshots

<img width="673" height="380" alt="Screenshot 1" src="https://github.com/user-attachments/assets/c13b892f-902c-4dc2-a757-5030b341bba5" />


<img width="673" height="380" alt="Screenshot 2" src="https://github.com/user-attachments/assets/25f3a5c3-4ca0-4ee1-ba79-d432835cb815" />


<img width="673" height="380" alt="Screenshot 3" src="https://github.com/user-attachments/assets/81955d21-442e-4206-93f8-e5d7813b13c6" />




---

**Conclusion:**
This Power BI dashboard for Awesome Chocolates successfully converts complex data into actionable insights, enabling leadership to make faster, smarter, and more profitable decisions.
