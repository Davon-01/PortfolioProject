# COVID-19 Global Health Analytics Baseline

## 📊 Live Interactive Dashboard
> 💡 **Link:** [Click here to execute the full interactive dashboard on Tableau Public] <https://public.tableau.com/app/profile/davon.shyu/viz/CovidDashboard_17798535652980/Dashboard1>

---

## 📋 Project Overview
This repository contains an end-to-end data analytics project focused on structuring, querying, and visualizing global public health data across a multi-year timeline (2021–2026). The objective was to transform millions of rows of raw data into accessible, corporate-level intelligence tracking post-peak infection stabilization and regional statistical variance.

The workflow involved executing advanced SQL data manipulation queries to aggregate metrics, followed by designing a localized visual layer within Tableau Public to serve as an interactive, self-serve diagnostic tool.

---

## 🛠️ Technical Competencies & Concepts Applied
* **Relational Database Design & Query Optimization:** Structured multi-layered query calculations using Common Table Expressions (CTEs) and Temporary Tables to optimize database processing execution speeds.
* **Data Aggregation & Manipulation:** Utilized advanced SQL syntax including `JOIN` clauses, `GROUP BY` functions, and conditional `WHERE` filters to isolate key trends.
* **Analytical Window Functions:** Applied `PARTITION BY` partitions combined with rolling `SUM` logic to compute dynamic, cumulative population metrics over continuous historical dates.
* **Business Intelligence & Dashboard Architecture:** Configured custom discrete and continuous date granularities, parameters, and interactive visual hierarchies to map raw mathematical outputs into clear executive trendlines.

---

## 📈 Dashboard Architecture Preview
Below is a static rendering of the reporting layer. To interact with the live charts, apply dynamic data filters, and view localized data tooltips, please utilize the **Tableau Public Link** located at the top of this page.

![Tableau Dashboard Preview](Covid%20Tableau%20Dashboard.png)

---

## 🗂️ Repository Inventory
* **[Covid_data_exploration.sql](./Covid_data_exploration.sql):** Contains the complete, production-ready SQL script detailing the database logic, schema joins, and data aggregation queries.
* **[Covid Tableau Dashboard.png](./Covid%20Tableau%20Dashboard.png):** High-resolution image asset capturing the main user interface design of the reporting layer.

---
*Data Source Credit: Publicly available global historical data compiled by Our World in Data.*
