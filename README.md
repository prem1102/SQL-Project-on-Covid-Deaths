COVID-19 Data Exploration Project
Overview
This project explores the global impact of the COVID-19 pandemic using SQL. The dataset includes information on COVID-19 cases, deaths, population, and vaccinations. The analysis employs advanced SQL techniques to uncover insights about infection rates, mortality rates, and vaccination progress across countries and continents.

Skills Demonstrated
Joins
Common Table Expressions (CTEs)
Temporary Tables
Window Functions
Aggregate Functions
Data Type Conversions
Creating Views
Datasets
CovidDeaths: Contains data on COVID-19 cases, deaths, and population by location.
CovidVaccinations: Contains data on vaccination progress by location and date.
Key Analyses
1. Initial Data Overview
Filtered data to exclude null continents and sorted by location and date for a cleaner view.
2. Total Cases vs. Total Deaths
Calculated the likelihood of dying from COVID-19 by dividing total deaths by total cases.
3. Total Cases vs. Population
Analyzed the percentage of the population infected with COVID-19.
4. Highest Infection and Death Rates
Identified countries with the highest infection rates relative to their populations.
Determined countries with the highest death counts.
5. Continental Analysis
Assessed continents with the highest death counts relative to their populations.
6. Global Numbers
Summarized global total cases, deaths, and the percentage of deaths relative to cases.
7. Vaccination Progress
Compared total population to vaccination data to calculate the percentage of the population vaccinated.
8. Advanced Techniques
Used CTEs, temporary tables, and views to simplify and organize complex queries.
Created a reusable view for visualizing vaccination data.
Highlights of SQL Techniques
Joins: Combined data from CovidDeaths and CovidVaccinations to correlate vaccination progress with population and infection data.
CTEs: Simplified partitioned calculations to derive rolling vaccination totals.
Temporary Tables: Stored intermediate results for subsequent calculations.
Window Functions: Used for cumulative calculations, such as rolling totals for vaccinations.
Aggregate Functions: Extracted maximum values and summed data to find key insights.
Usage
This SQL project is designed for analytical purposes and can be integrated with visualization tools like Power BI or Tableau for graphical representation of the insights derived.

Future Work
Expand analysis to include trends over time using date-based grouping.
Incorporate demographic data for more granular insights.
Visualize results for better communication of key findings.
Conclusion
This project demonstrates the power of SQL in data exploration and analysis. It showcases how complex queries can yield actionable insights into a global crisis like the COVID-19 pandemic.
