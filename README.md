# 🍕 Pizza Sales Analysis | SQL Server & Power BI

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

> **End-to-End Sales Analytics Project — SQL Server Querying & Interactive Power BI Dashboard**

An end-to-end data analytics project analyzing pizza sales data using **SQL Server** and visualizing the results in an interactive **Power BI** dashboard to uncover customer ordering patterns, peak demand periods, and product performance.

![Pizza Sales Dashboard Preview](images/dashboard.png)

---

## 📊 Key Performance Indicators (KPIs)
| Metric | Value |
| :--- | :--- |
| **Total Revenue** | $817,860 |
| **Average Order Value** | $38.31 |
| **Total Pizzas Sold** | 49,574 |
| **Total Orders** | 21,350 |
| **Average Pizzas Per Order** | 2.32 |

---

## 🔍 SQL Analysis Highlights
Used **SQL Server** to validate KPIs and extract analytical insights using:
* **Aggregations & Grouping:** `SUM`, `COUNT`, `GROUP BY`, and `ORDER BY`
* **Advanced Querying:** Subqueries and `DISTINCT`
* **Time Intelligence:** Date functions (`DATENAME`, `DATEPART`, `MONTH`)
* **Filtering & Formatting:** `WHERE` filtering and `CAST` for numerical formatting

---

## 💡 Key Business Findings
* **Peak Day:** **Friday** recorded the highest number of orders.
* **Peak Hour:** **12 PM** was the busiest ordering hour of the day.
* **Top Category:** **Classic** pizzas contributed the highest sales share (**26.91%**).
* **Top Size:** **Large** pizzas represented the highest sales share by size (**45.89%**).
* **Best-Selling Product:** The **Classic Deluxe Pizza** ranked #1 by quantity sold.

---

## 🛠️ Tech Stack
* **Database & Querying:** Microsoft SQL Server
* **BI & Visualization:** Microsoft Power BI (Interactive Charts, KPI Cards, Date Slicers)

---

## 🚀 How to View
1. Review the SQL scripts in this repository to see the KPI validation and exploratory queries.
2. Download the `.pbix` file and open it in **Microsoft Power BI Desktop**.
3. Use the interactive date slicer and filters to explore daily/hourly trends and top/bottom 5 products.
