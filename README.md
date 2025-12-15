Project Objective:

USA Emission Dashboard analyzes air-pollution / emission data across the United States using EPA (Environmental Protection Agency) data.
The main goals are to:
Understand geographical emission distribution
Compare emissions per person by population
Identify top contributing states
Build an interactive analytics dashboard using Databricks.




Data Source:

Source: USA – Environmental Protection Agency (EPA)
Year: 2025
Type of data:
State-wise emissions
Location (latitude, longitude)
Population
Emission per person
Contribution percentage (pct_of_total)
State abbreviation (state_abbr)
This is real-world public data, commonly used in analytics and data engineering demos.

Tools & Architecture Used:


🧰 Tools
Databricks Community Edition
Spark SQL
Databricks SQL Dashboard
Serverless SQL Warehouse



Dashboard Visual Explanation:

🗺️ 1. Emission Based on Location (Map Visualization)

What it shows:
Geographic distribution of emission sources across the USA
Each dot represents an emission source or data point
Why it’s useful:
Identifies emission hotspots
Shows regional concentration (industrial areas, cities)
Skills demonstrated:
Geospatial visualization
Latitude & longitude mapping
Databricks map integration (Mapbox).

📊 2. Emissions per Person Over Population (Scatter Plot)

X-axis: Emission per person
Y-axis: Population
What it shows:
Relationship between population size and per-capita emissions
States with high emissions but low population stand out
Business insight:
Small population ≠ low emissions
Helps policymakers target high per-capita emission states
Skills demonstrated:
Data normalization
Scatter analysis
Correlation analysis.

🥧 3. Top States Emission Contribution (Pie Chart)

Metric: SUM(pct_of_total)
Color: state_abbr (TX, FL, OH, IL, etc.)
What it shows:
Top 10 states contributing to total emissions
Percentage share of each state
Why it matters:
Identifies major contributors like Texas, Florida, Ohio
Helps in prioritizing emission control policies
Skills demonstrated:
Aggregation (SUM)
Ranking (Top-N analysis)
KPI-style visualization

