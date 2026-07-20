# 📊 Sales Dashboard & Commercial Analytics — Power BI & SQL

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC292B?style=flat&logo=microsoftsqlserver&logoColor=white)

## 📌 Project Overview
This project features an interactive **Sales Dashboard** developed in **Power BI**, backed by a structured data architecture modeled in **SQL Server**. The primary goal is to provide commercial leadership with clear insights into revenue performance, time-series growth, and Average Order Value (AOV) behavior per customer.

---

## 📸 Dashboard Preview
![Sales Dashboard Overview](screenshot_1.png)
![Sales Dashboard Overview](screenshot_2.png)

---

## 🎯 Key Metrics & Features
- **Net Revenue:** Consolidated financial view excluding noise and returns.
- **Year-over-Year (YoY) Analysis:** Performance comparison against the same period in the previous year to track true business growth.
- **Average Order Value (AOV / Ticket Médio):** Metric used to evaluate purchasing profiles and revenue generated per transaction.
- **Dynamic Filtering:** Slicers for time periods (Year/Month), product categories, and sales channels.

---

## 🛠️ Tech Stack & Methods
- **SQL Server:** Custom queries and views for data cleaning, handling returns/cancellations, and aggregating raw transactional data.
- **Power BI (DAX):** Measures built using time intelligence functions (`SAMEPERIODLASTYEAR`, `CALCULATE`, `SUMX`).
- **Data Modeling:** Structured following the **Star Schema** architecture (Fact and Dimension tables) to ensure optimal report performance.

---

## 📂 Repository Structure
- `/sql/`: SQL scripts for database views and data transformation.
- `/pbix/`: Power BI project file (`.pbix`).
- `/images/`: Screenshots and visual assets.

---

## 👨‍💻 Author
**Wilton Aguiar**  
[LinkedIn](https://www.linkedin.com/in/wilton-aguiar) | [GitHub](https://github.com/WiltonAguiar)
