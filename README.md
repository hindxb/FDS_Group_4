# FDS
Foundation of Data Science Course - UOS

Assignemnt 1

The idea of this activity is to work in groups to analyze a dataset generated in California in 2020 about the Air Quality:

Columns:
- Date: Day/Month/year
- Daily Mean PM2.5 Concentration: Average PM2.5 concentration for the day
- AQI: Air Quality Index derived from PM2.5 levels
- CBSA Name: Core-Based Statistical Area
- County Name: County where the measurement was taken
- etc.

You are required to download the dataset shared in the Colab file to begin, the goal is to explore the dataset structure and perform some operations such as sorting, filtering, and selecting rows to extract meaningful insights.

To open it in colab:
https://colab.research.google.com/github/hindxb/FDS/blob/main/Notebooks/Class%20Activities/Group_4_AirQuality_Analysis.ipynb
 
Assignment 2:

Gapminder Health & Economy Analysis
Objective
In this project, you will work in teams to explore global health and economic data. The goal is to investigate the relationship between wealth, health, and population using two separate Gapminder datasets.

The datasets share a common key (country) and must be joined (merged by column) to answer meaningful research questions.

Datasets
Two CSV files are provided:

File	Description
Gapminder_Health.csv	Country, Year, Continent, Life expectancy, Population
gapminder_economy.csv	Country, Year, GDP per capita
Note: Both datasets contain one row per (country, year) pair. They share the country and year columns but carry different variables. You must join them on country to get a combined view for analysis.

Task Overview
- Load both CSV files.
- Merge the datasets using the common key (country and optionally year).
- Explore relationships between:
- GDP per capita and life expectancy
- Population trends over time
- Continental differences in health and wealth
- Draw conclusions and visualize key insights.
