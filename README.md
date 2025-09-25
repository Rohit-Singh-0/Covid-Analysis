COVID-19 Global Data Analysis & Dashboard
=========================================


### [View the Interactive Tableau Dashboard]([https://www.google.com/search?q=https://public.tableau.com/views/CovidDashboardTutorial_17587934353110/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link](https://public.tableau.com/views/CovidDashboardTutorial_17587934353110/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))


Project Overview
----------------


This project is an end-to-end data analysis of global COVID-19 data. The primary goal was to extract raw data, perform transformations and aggregations using advanced SQL, and create a comprehensive, interactive dashboard in Tableau to visualize key trends and metrics.


The analysis covers global numbers, continental breakdowns, and country-specific trends related to infections, deaths, and vaccinations.


Data Sources
------------


The data for this project was sourced from Our World in Data and is contained in two main tables:


*   **CovidDeaths:** Contains data on confirmed cases, deaths, and population by country.
    
*   **CovidVaccinations:** Contains data on vaccination numbers and rollouts.
    


Technical Skills & Tools Used
-----------------------------


*   **Data Transformation & Analysis:** SQL Server
    
    *   Utilized **CTEs (Common Table Expressions)** and **Temp Tables** to structure complex queries.
        
    *   Employed **Window Functions** (OVER (PARTITION BY ...) to calculate rolling vaccination numbers.
        
    *   Used **Joins**, **Aggregate Functions** (SUM, MAX), and **Data Type Conversions** (CAST, CONVERT).
        
    *   Created **SQL Views** to store transformed data for easy import into Tableau.
        
*   **Data Visualization:** Tableau Public
    
    *   Developed a multi-sheet dashboard with interactive filters.
        
    *   Used geographic maps, bar charts, line graphs, and KPI cards to tell a clear story.
        


Key Questions Addressed
-----------------------


The analysis and dashboard were designed to answer several key questions:


1.  What are the global totals for cases, deaths, and the overall death percentage?
    
2.  Which continents have the highest death counts?
    
3.  What is the percentage of the population infected in each country, and how does it trend over time?
    
4.  How does the rolling count of new vaccinations progress for each country?
    


The Process
-----------


1.  **Data Exploration:** The initial phase involved exploring the raw datasets to understand the structure, data types, and potential inconsistencies.
    
2.  **Data Transformation (SQL):** A series of SQL queries were written to join the two tables, calculate new metrics (like DeathPercentage), and aggregate data at different levels (global, continental, country). The full script can be found in the COVID Portfolio Project - Data Exploration.sql file in this repository.
    
3.  **Dashboard Creation (Tableau):** The cleaned and aggregated data, stored in SQL Views, was connected to Tableau. The dashboard was then built with a focus on user experience, allowing for easy filtering and drill-down into the data.
    


How to Use This Repository
--------------------------


*   **SQL Script:** The .sql file contains all the queries used for the data exploration and transformation.
    
*   **Tableau Link:** The link at the top of this Readme will take you to the interactive public dashboard.
