# 🏥 Apollo Health Care Hospital — SQL | Power BI | Excel  

![Project Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?style=flat-square)
![SQL](https://img.shields.io/badge/Database-SQL-blue?style=flat-square)
![Excel](https://img.shields.io/badge/Data-Excel-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

---

## 📊 Project Overview

The goal of this project is to analyze hospital datasets to uncover insights related to:
-Patient admissions & discharge trends
-Department-wise performance
-Doctor workload & efficiency
-Billing and revenue analytics
-Appointment patterns
-Emergency vs OPD flow

This project showcases my ability to work with large datasets, perform ETL pipelines, and build interactive dashboards for business decision-making.

---

## Project Workflow

1️⃣ Data Collection & Cleaning (Excel)

-Handled missing values
-Standardized formats (dates, ID, billing codes)
-Cleaned duplicates
-Created helper columns (age group, service category,     visit type)

2️⃣ Data Loading & Transformation (SQL)

-Imported Excel sheets into SQL tables
-Designed relational schema
-Applied joins, window functions, CTEs
-Performed aggregations for department & doctor-wise metrics
-Created reusable SQL views for dashboards

3️⃣ Data Visualization (Power BI)

Developed an interactive, user-friendly dashboard displaying:

✔ Patient Admission Trends
✔ OPD vs IPD Summary
✔ Department Utilization
✔ Doctor Performance KPIs
✔ Billing & Revenue Analysis
✔ Daily, Monthly, Quarterly Insights

4️⃣ Insights & Recommendations

Some key insights (example):

-Cardiology department had the highest patient inflow
-Peak admissions occur between 10 AM – 2 PM
-Revenue increased by 18% YoY
-High patient no-show rate in outpatient appointments

---

## 🗂️ Project Structure
├── data/
│   ├── apollo_raw_data.xlsx
│   ├── cleaned_data.csv
│   └── sql_queries.sql
│
├── powerbi/
│   └── Apollo_Hospital_Dashboard.pbix
│
├── images/
│   ├── dashboard_overview.png
│   └── key_visuals.png
│
├── README.md
└── LICENSE (optional)


---

## 🧩 Tools & Technologies

This project uses a complete analytics ecosystem covering data cleaning, storage, processing, and visualization.

🔹 Excel
 -Raw data exploration & profiling

 -Data cleaning and formatting

 -Pivot tables for quick summaries

 -Creating helper columns (Age groups, visit category,  billing classifications)

🔹 SQL (MySQL / SQL Server)
-Data modeling and relational design
-High-performance querying using joins, CTEs, window functions
-Data transformation and building analytical views
-KPI generation (department revenue, doctor workload, patient stay duration)

🔹 Power BI

Interactive dashboards and hospital KPIs

DAX measures for hospital metrics

Slicers and bookmarks for user navigation

Report-level and page-level drill-downs

🔹 Data Analysis Techniques

Descriptive analytics (trends, counts, averages)

Time-series analysis

Patient and department segmentation

KPI comparisons (MoM, YoY)

Healthcare-specific insights (bed occupancy, OPD load, emergency flow)
---

## 📈 Key Insights & Visuals
The dashboard highlights several operational dimensions:

1. Patient Admission Trends
 -Daily/monthly admission patterns
 -OPD vs IPD comparison
 -Peak visiting hours
 
2. Department-wise Performance
 -Most visited departments
 -Average waiting time
 -Doctor-wise patient load

3. Financial Insights
 -Revenue trends
 -Department-wise billing contribution
 -Insurance vs cash patient distribution

4. Clinical KPIs
 -Bed occupancy rate
 -Average Length of Stay (ALOS)
 - Readmission rates

Power BI Visuals Include:
-Line charts
-Bar/column charts
-Donut/Pie charts
-KPI cards
-Slicers & interactive filters
-Drill-through and bookmarks

---
## 🧾 Acknowledgement

Special thanks to:
-Apollo Hospital sample dataset (or your created dataset).
-Power BI community documentation.
-SQL and Excel communities for query & formula references. 

---

## 🔌 API Reference

Patient Data API-
 GET /api/patients
Parameters: id, date_range
Response: JSON patient records

Billing API-
GET /api/billing
Returns department-wise revenue details



---

## 📚 Appendix

1. The dataset includes patient, billing, and department   details cleaned using Excel and SQL.

2. SQL queries for preprocessing and aggregations are stored in sql_queries.sql.

3. Key Power BI DAX measures used: Total Revenue, ALOS, Bed Occupancy, and Patient Count.

4. Dashboard visuals are based on anonymized or dummy hospital data.

5. Future improvements include API integration, predictive analytics, and cloud deployment

---

## 👨‍💻 Authors

**Praveen Keshari**  
*Data Analyst | SQL | Power BI | Excel | Data Visualization*  
📧 [kpraveen4445@gmail.com](mailto:praveenkeshari@example.com)  
💼 [LinkedIn Profile](https://www.linkedin.com) 

---

## 🏅 Badges

![SQL](https://img.shields.io/badge/Skill-SQL-blue?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Skill-Power%20BI-yellow?style=for-the-badge)
![Excel](https://img.shields.io/badge/Skill-Excel-green?style=for-the-badge)
![Data Analytics](https://img.shields.io/badge/Domain-Data%20Analytics-orange?style=for-the-badge)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE) — feel free to use and modify it with proper attribution.

---

⭐ **If you like this project, don’t forget to give it a star on GitHub!**

## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Appendix
1. The dataset includes patient, billing, and department   details cleaned using Excel and SQL.

2. SQL queries for preprocessing and aggregations are stored in sql_queries.sql.

3. Key Power BI DAX measures used: Total Revenue, ALOS, Bed Occupancy, and Patient Count.

4. Dashboard visuals are based on anonymized or dummy hospital data.

5. Future improvements include API integration, predictive analytics, and cloud deployment

## Authors

**Praveen Keshari**  
*Data Analyst | SQL | Power BI | Excel | Data Visualization*  
📧 [kpraveen4445@gmail.com](mailto:praveenkeshari@example.com)  
💼 [LinkedIn Profile](https://www.linkedin.com)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Apollo Health care Hospital