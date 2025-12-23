🌍 Energy Consumption Analysis (MySQL Project)
📌 Project Overview

The Energy Consumption Analysis project uses MySQL to analyze global energy and economic data across countries and years.
The project focuses on understanding energy consumption, production, carbon emissions, GDP, and population trends using pure SQL queries.

This project demonstrates strong skills in database design, relational modeling, and SQL-based data analysis.

🎯 Objectives

Analyze global energy consumption patterns

Compare energy production vs consumption

Study carbon emission trends across countries

Understand the impact of GDP and population on energy usage

Extract meaningful insights using MySQL only

🏢 Business Problem

Global energy demand is increasing due to population growth and economic development, leading to higher carbon emissions and environmental concerns.
However, energy-related data is often scattered across multiple sources, making analysis difficult.

This project solves the problem by integrating energy, economic, and population data into a structured MySQL database, enabling data-driven insights for sustainable energy planning and policy decisions.

📂 Dataset Description

The dataset consists of six CSV files, each representing a specific domain of global energy and economic data. These files were imported into MySQL and linked using relational keys.

Tables Used:

country_3 – Central reference table containing country names

consum_3 – Energy consumption data by country and year

production_3 – Energy production data

emission_3 – Carbon emission details

gdp_3 – GDP data of countries

population_3 – Population statistics

All tables are connected through the country field, ensuring data consistency and integrity.

🗂️ Database Design

Relational database structure

country_3 acts as the central table

Foreign key relationships reduce data redundancy

Ensures data integrity across all datasets

Supports efficient multi-table SQL analysis

🛠️ Tools & Technologies Used

MySQL – Database creation and querying

SQL – Data analysis and reporting

CSV Files – Source data format

GitHub – Project hosting and documentation

🔍 SQL Concepts Applied

Database and table creation

Primary keys and foreign keys

INNER JOIN operations

Aggregate functions (SUM, AVG, MAX, MIN)

GROUP BY and ORDER BY

Subqueries

Filtering using WHERE and HAVING

📊 Sample Analysis Performed

Total energy consumption by country

Comparison of production vs consumption

Year-wise emission analysis

GDP vs energy consumption comparison

Per-capita emission calculations

Identification of top emitting countries

📈 Key Insights

A small number of countries account for a major share of global energy consumption

Countries with higher GDP tend to consume more energy

High population does not always mean higher per-capita consumption

Emission levels vary significantly based on energy production methods

✅ Conclusion

This project demonstrates how MySQL alone can be effectively used for real-world data analysis.
By integrating multiple datasets and applying structured SQL queries, meaningful insights were derived to understand global energy usage and its environmental impact.
