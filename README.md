# Paralympic-Dashboard
🏅 Paralympic Games Dashboard (Power BI Project)
🔍 Overview
This interactive dashboard provides deep insights into the performance of countries across multiple editions of the Paralympic Games. Built using Power BI, the dashboard analyzes medals, rankings, geographic trends, and participation statistics using DAX formulas and interactive visualizations.

🎯 Project Purpose
The purpose of this project is to demonstrate expertise in data modeling, transformation, and visual storytelling using Power BI. It highlights my ability to convert raw data into actionable insights—ideal for decision-making, performance monitoring, and presentation in analytics interviews.

📁 Dataset Source
Kaggle - Paralympic Games Dataset 

Cleaned and transformed data using Power Query and calculated fields

🛠 Tech Stack
Power BI Desktop – Visualization & Dashboarding

Power Query (M Language) – Data transformation

DAX (Data Analysis Expressions) – Calculated metrics and measures

Excel / CSV – Base data manipulation

📊 Key Visualizations & Features
Bar Chart – Top 10 countries by Gold medals

Pie Chart – Continent-wise medal share

Map Chart – Geographic visualization of medal winners

Column Chart – Silver/Bronze comparison by country

Area Chart – Year-wise medal growth

Donut Chart – Medal share by rank type (Gold, Silver, Bronze)

Line Chart – Medal trends over years for top performers

Cards & KPIs – Total Medals, Countries, Participation

Slicer – Filter by season, year, rank type

Table View – Country contribution % and average rank

🧮 DAX Measures Used
Total Medals = npc_gold + npc_silver + npc_bronze

Gold Share % = npc_gold / Total Medals

Silver Share % = npc_silver / Total Medals

Bronze Share % = npc_bronze / Total Medals

Country Contribution % = SUM(Total Medals) / TOTAL(Total Medals)

Average Rank = AVERAGEX(VALUES(npc_name), npc_rank)

✅ Skills Demonstrated
Data Cleaning & Transformation (Power Query)

DAX Formulas & Advanced Aggregation

KPI & Metric Creation

Geo & Trend Visualization

Dashboard UX Layout for Storytelling

Self-driven Analysis & Insight Communication

📌 Screenshots

![Paralympic Dashboard Overview](https://github.com/Daykumar999/Paralympic-Dashboard/blob/main/Snapshot%20of%20Dashboard.png)
![Paralympic Dashboard Overview](https://github.com/Daykumar999/Paralympic-Dashboard/blob/main/Snapshot%20of%20Report.png)


