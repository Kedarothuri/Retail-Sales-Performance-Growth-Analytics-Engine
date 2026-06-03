# Retail-Sales-Performance-Growth-Analytics-Engine
An end-to-end data analytics project leveraging SQL Server for advanced data querying and Power BI for executive-level performance tracking, featuring optimized time-intelligence and localized ranking models.

# Retail Sales Performance & Growth Analytics Engine

An end-to-end retail data analytics solution designed to transform raw transactional history into interactive, business-ready intelligence. This project spans database engineering using **SQL Server** and dynamic visualization modeling using **Power BI**.

## 🚀 Key Project Highlights
* **Advanced Database Querying:** Engineered robust SQL queries featuring Common Table Expressions (CTEs), window partitioning (`ROW_NUMBER() OVER`), and conditional aggregation to segment historical records.
* **Memory-Optimized DAX Architectures:** Resolved data engine resource bottlenecks by restructuring heavy calculated columns into highly optimized, localized row-context evaluations (`RANKX`, `CALCULATETABLE`, and `ALLEXCEPT`), dropping in-memory query cache footprints significantly.
* **Executive Metrics Dashboarding:** Modeled core business KPIs alongside granular analytics to monitor temporal shifts, distribution channel health, and structural growth.

## 📊 Dashboard Visualizations Included
1. **Regional Demand Metrics:** Dynamically isolates and ranks the top 5 revenue-generating items within individual country borders to eliminate inventory supply bottlenecks.
2. **Month-over-Month (MoM) Growth Trends:** Plots side-by-side time-series comparisons between 2022 and 2023 financial performance to reveal seasonal spikes and customer behavior shifts.
3. **Year-over-Year (YoY) Profitability Vectors:** Utilizes interactive conditional formatting matrix elements to separate accelerating product subcategories from stagnating lines.

## 🛠️ Tech Stack & Concepts Used
* **SQL Server:** Aggregations, Window Functions, Table Partitions, CTEs
* **Power BI Desktop:** DAX (Data Analysis Expressions), Data Modeling, Context Transition Optimization
