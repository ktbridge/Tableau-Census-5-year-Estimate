# Tableau-Census-5-year-Estimate

This repository contains Tableau dashboards built using Census 4-Year Estimates (2019–2023).
The dashboards provide an interactive view of key demographic and economic indicators across U.S. states.


📊 Data Sources

The dashboards are based on annual Excel files for the years:

2019.xlsx

2020.xlsx

2021.xlsx

2022.xlsx

2023.xlsx

Each file contains census estimates at the state level.


🛠️ Data Collection

The raw data was obtained from the U.S. Census Bureau using two approaches:

Census API — for structured demographic and economic datasets.

BeautifulSoup (Python) — for web scraping supplementary tables when API endpoints were not available.

The collected data was cleaned and exported into Excel format (.xlsx) for consistency across the five years.


🗂️ Data Dictionary

Column	Description:

- State	U.S. state or territory name
- Population	Estimated total population
- Median Age	Median age of the population
- Household Income	Median household income (in USD)
- Per Capita Income	Average income per individual (in USD)
- Poverty Count	Number of people living below the poverty line
- Poverty Rate	Percentage of the population living below the poverty line (%)


📈 Dashboards

The Tableau dashboards provide interactive analysis of:

- Population trends (2019–2023)

- Median age shifts across states

- Household & per capita income comparisons

- Poverty counts and rates over time





🚀 Usage

Clone this repository:

| git clone https://github.com/your-username/your-repo-name.git


Open the Tableau workbooks (.twb / .twbx) inside Tableau Desktop or Tableau Public.

Explore interactive dashboards.



📌 Notes

Data is aggregated at the state level.

All values are sourced from U.S. Census 4-year estimates (2019–2023).

Dashboards are optimized for interactive exploration.
