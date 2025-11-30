🦠 COVID-19 Data Analysis Using SQL

Comprehensive Global COVID-19 Insights (Cases, Deaths & Vaccinations)
This repository contains an end-to-end COVID-19 Data Exploration & Analysis Project performed using Microsoft SQL Server.
The goal of the project is to understand the global impact of the COVID-19 pandemic by analyzing case trends, death rates, population infection rates, and vaccination progress across countries and continents.

The analysis is conducted on datasets sourced from the World Health Organization (WHO) and includes multiple curated SQL queries, views, and transformations to derive meaningful insights.

📌 Project Overview
Using SQL, this project dives deep into:
Global COVID-19 cases & deaths
Infection rates by country
Death ratios across continents
Vaccination rollout across the world
Country-level population vs vaccination progress
Rolling vaccination metrics
Creation of reusable SQL Views for BI dashboards
This analysis provides a data-driven view of how COVID-19 affected different regions and how vaccination efforts progressed globally.

📊 Key Business Questions Answered

The following insights were generated from the analysis:
What percentage of each country’s population was infected?
Which countries had the highest infection rate relative to population?
Which continents experienced the highest total death count?
What does the global case-to-death ratio look like?
How many people were vaccinated over time by location?
What percentage of a population received at least one vaccine dose?
What are the trends of cases vs deaths for specific countries (e.g., Nigeria)?
(Insight generation supported by the SQL code in the analysis files 
My_Microsoft_SQL_Portfolio_Proj…
.)

🗂️ Repository Structure
📦 COVID-19-SQL-Analysis
│
├── CovidDeaths.xlsx                   # Raw COVID-19 deaths dataset
├── CovidVaccinations.xlsx             # Raw vaccination dataset
├── Covid_Deaths_Full_Dataset.xlsx     # Combined dataset
├── Covid19 Image.jpg                  # Project banner image
├── My_Microsoft_SQL_Portfolio_Projects.txt     # SQL reference notes
├── Covid19 Vaccination Data Analysis.txt        # Complete SQL Queries (Used for analysis)
└── README.md                           # Project documentation

🛠️ Tools & Technologies

Microsoft SQL Server
T-SQL (CTEs, Joins, Temp Tables, Window Functions)
Excel / CSV WHO Dataset
SQL Server Views for BI and reporting

🧠 Core SQL Techniques Used

The project demonstrates strong SQL analytics skills:
Window Functions (OVER (PARTITION BY ...))
Aggregate Functions
Common Table Expressions (CTEs)
Temp Tables
Data Cleaning and Filtering
Creating SQL Views for downstream tools (Power BI, Tableau)

📈 Key Insights From the Analysis

1. Global Aggregation Metrics
The project calculates total global cases, deaths, and the overall fatality rate.

2. Infection Rate by Country
Identifies countries with the highest infection percentage relative to population.

3. Death Count by Continent
Evaluates continents with the highest death counts.

4. Vaccination Progress
Rolling vaccination totals were computed using window functions to determine:
How fast different countries vaccinated their populations
Percentage of population vaccinated over time

5. Country-Specific Case vs Death Trends
Includes dedicated analysis for countries such as Nigeria, assessing fatality risk.

🏗️ SQL Views Created in the Project

Reusable SQL Views include:
PercentPopulationVaccinated
GlobalDeaths
Death_by_Continent
CountryWithHighestDeaths
HighestInfectionRate
TotalCasesPercentageInfected
TotalCasesvsTotalDeaths
CasesvsDeaths

(Full view definitions are available in the SQL analysis file My_Microsoft_SQL_Portfolio_Proj.)

📘 How to Use This Project

Download the datasets provided in the repository
Import them into SQL Server
Run the SQL scripts from the analysis file
Use the final Views for visualization or BI dashboards
Extend the analysis using additional metrics as needed

🎯 Conclusion

This project showcases in-depth SQL data analysis capabilities using real-world global pandemic data.
It demonstrates:

Complex SQL querying
Data transformation
Analytical thinking
Reporting readiness for BI tools

The insights generated here can serve as a foundation for deeper epidemiological research or interactive dashboards.
