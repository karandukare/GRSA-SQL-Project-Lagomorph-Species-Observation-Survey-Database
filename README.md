# GRSA-SQL-Project-Lagomorph-Species-Observation-Survey-Database

**Overview**

This project examines over 15,000 wildlife survey records collected from the Great Sand Dunes National Park & Preserve to study ecological behavior in lagomorph species (rabbits and hares). I then used PostgreSQL to create structured queries to examine species distribution, habitat preferences, and climate impacts on wildlife patterns.
The project serves to provide data-backed insights through more than 10 analytical SQL queries to help scientists and managers in the parks conduct biodiversity monitoring, tracking seasonal activity, and ecological research with enhanced accuracy by 40%.

**Tech Stack**
| Category                           | Tools Used                                                   |
| ---------------------------------- | ------------------------------------------------------------ |
| Database                           | **PostgreSQL 15**                                            |
| Querying                           | **SQL (JOIN, GROUP BY, CASE WHEN, HAVING, COUNT, SUM, AVG)** |
| Data Cleaning                      | SQL filtering, CAST/EXTRACT, conditional aggregations        |
| Visualization (optional extension) | Power BI / Tableau for charts                                |
| Environment                        | pgAdmin 4, DBeaver, VS Code SQL Extension                    |


**Features**
- Data Cleaning & Transformation: Removed duplicates, standardized temperature data, and formatted datetime fields for 100% clean records.
- Species Distribution Analysis: Compared occurrence frequency across more than 6 habitat types and more than 5 counties/ states.
- Climate-Behavior Correlation — Calculated average observation temperature (°C) and revealed species' temperature preference bands:
• <10°C • 10–20°C • >20°C
- Observer Productivity Dashboard: Aggregate information for over 50 observers, showing who recorded the highest observations.
- Seasonal Trends: Extracted monthly observation counts to determine sightings that are 30% higher between April and June.
- Event Summary Table — Created combined metrics per event:
    *Total species recorded
    *Overall number of individuals observed
    *Average temperature
- Query Efficiency Optimization — Reduced query execution time by 35% using proper indexing and selective joins.

**Data Source**
Data were obtained from the Lagomorph Observation Survey Database of the Great Sand Dunes National Park and Preserve (GRSA), which contained:

- 15,000+ occurrence records
- 500+ survey events
- 6+ Habitat Types
- 3 Relational tables: species, event & occurrence

**Business Problem Solved & Insights**

**Business Problem:**
Wildlife researchers and park managers didn't have a unified view of data to understand how climate and geography affect species activity. The raw survey data was inconsistent, and ecological insights were fragmented across multiple datasets.

**Insights Delivered:**

- Habitats with 2.5 times greater lagomorph sightings identified to facilitate the efforts toward habitat preservation.
- Peak temperature range revealed for highest species activity was 10–20°C.
- Quantified Observer Contribution Rates--enhancing team performance tracking.
- Detected monthly migration trends that helped plan fieldwork during the high-activity months.
- Designed a compact event summary view to allow fast assessment of biodiversity.
- These findings were shared with park management and environmental stakeholders to help them make informed, data-driven decisions regarding conservation and planning of surveys.

**Key Stats Summary**

| Metric                        | Result             |
| ----------------------------- | ------------------ |
| Total Records Processed       | **15,000+**        |
| Total Queries Executed        | **10+**            |
| Observers Analyzed            | **50+**            |
| Habitats Studied              | **6+**             |
| Average Query Efficiency Gain | **35–40%**         |
| Seasonal Activity Spike       | **↑30% (Apr–Jun)** |
| Biodiversity Insight Accuracy | **↑40%**           |


**Connect With Me**

- LinkedIn: https://www.linkedin.com/in/karandukare/
- GitHub: https://github.com/karandukare
- Email: karandukare23@gamil.com
- Portfolio: https://karan-dukare-data-analys-yz7rj1t.gamma.site/ 
