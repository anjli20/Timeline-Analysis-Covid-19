# COVID-19 Timeline Analysis

##  Overview

This project performs an exploratory data analysis (EDA) and timeline analysis of the COVID-19 pandemic using the [Our World in Data](https://ourworldindata.org/covid-deaths) dataset. The goal is to visualise the global spread of COVID-19, identify the most affected 
countries, and understand the relationships between key metrics such as total cases, deaths, and testing rates.

##  Dataset

Data Set Link- https://bit.ly/30d2gdi

- **Source:** `owid-covid-data.csv` (Our World in Data)
- **Size:** 115,893 rows × 62 columns
- **Key Features:** `total_cases`, `new_cases`, `total_deaths`, `new_deaths`, `total_tests`, `positive_rate`, `continent`, `location`, `date`, and more.


## Analysis Performed

- **Data Preprocessing** — null value inspection, data types, shape, and descriptive statistics
- **World Choropleth Map** — total COVID-19 deaths visualised by country using Plotly
- **Top 10 Countries** — ranked by new cases and total deaths (globally and within Asia)
- **Asia-Specific EDA** — filtered dataset for Asian countries with correlation heatmap
- **Line Graphs:**
  - Total Cases vs Total Deaths
  - Total Deaths vs New Deaths per Million
  - Total Tests vs Positive Rate


## Key Findings

- The **United States** recorded the highest number of new cases and total deaths globally as of 15 November 2020.
- **Brazil** and **India** followed closely in both categories.
- Within Asia, **India** had the most cases, while **Laos**, **Timor**, and **Brunei** had the least.
- A clear positive correlation exists between total cases and total deaths.
- New deaths per million spiked sharply early in the pandemic before gradually declining.
- The positive test rate initially rose with increased testing, then declined, before rising again.
