🌍 Energy Consumption Analysis
📌 Project Overview

The Energy Consumption Analysis project focuses on analyzing global energy data to understand the relationship between energy consumption, production, emissions, GDP, and population across different countries and years.
The goal is to convert raw energy data into meaningful insights that support sustainable energy planning and data-driven decision making.

This project uses SQL for data analysis and Power BI for visualization to identify trends, comparisons, and key patterns in worldwide energy usage.

🎯 Objectives

Analyze energy consumption and production trends by country and year

Compare carbon emissions across countries

Study the relationship between GDP, population, and energy usage

Identify top energy-consuming and emitting countries

Generate insightful dashboards for better understanding and presentation

🏢 Business Problem

Global energy demand is increasing due to population growth and economic development. However, heavy dependence on fossil fuels leads to higher carbon emissions and environmental impact.
There is a lack of integrated, data-driven analysis that connects energy consumption, production, emissions, GDP, and population.
This project aims to bridge that gap by providing clear insights that help policymakers, organizations, and analysts understand energy patterns and support sustainable energy strategies.

📂 Dataset Information

The dataset is sourced from global energy and economic data providers and includes multiple CSV files imported into a MySQL database.

Tables Used:

country – Central reference table containing country names

consumption – Energy consumption data by country and year

production – Energy production data

emission – Carbon emission details

gdp_ppp – GDP data based on Purchasing Power Parity

population – Population statistics

Each table is linked using foreign key relationships with the country table.

🗂️ ER Diagram Overview

The country table acts as the central dimension table

Other tables store fact data related to energy, emissions, GDP, and population

Relationships ensure data integrity and reduced redundancy

🛠️ Tools & Technologies Used

MySQL – Data storage, table creation, and querying

SQL – Data analysis and transformations

Power BI – Interactive dashboards and data visualization

Excel / CSV – Raw data format

GitHub – Version control and project sharing

📊 Key Analysis Performed

Total energy consumption and production by country

Year-wise emission trends

Per-capita energy consumption and emissions

Top countries by GDP and emissions

Comparison between developed and developing countries

Energy efficiency insights using production vs consumption

📈 Power BI Dashboard Highlights

Country-wise energy consumption trends

Emissions comparison across years

GDP vs energy usage analysis

Interactive filters for country and year

Clean and presentation-ready visuals

🔍 Key Insights

A small number of countries contribute to a major share of global energy consumption and emissions

Higher GDP generally correlates with higher energy usage

Fossil fuels dominate global energy production, increasing emissions

Per-capita energy usage varies significantly between countries

✅ Conclusion

This project demonstrates how data analytics and visualization can be used to understand complex global energy patterns. The insights derived from this analysis can support policy decisions, sustainability planning, and energy optimization strategies.
