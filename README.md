# Project: Data Analysis on Energy and GDP

## Overview

In this project, we analyze data related to energy supply, renewable energy production, and GDP of different countries to gain insights into the world's energy landscape. The dataset is collected from different sources, including the United Nations and the World Bank.

The primary objective of this project is to clean and merge the datasets to create a new dataset that contains the most relevant information required for analysis. We use pandas library to perform data cleaning, merging, and analysis.

## Project Steps

### The project consists of the following main steps:

1. Load the energy data from the file Energy Indicators.xls
2. Load the GDP data from the file world_bank.csv
3. Load the Sciamgo Journal and Country Rank data from the file scimagojr-3.xlsx
4. Join the three datasets: GDP, Energy, and ScimEn into a new dataset using the intersection of country names.
5. Use only the last 10 years (2006-2015) of GDP data and the top 15 countries by Scimagojr 'Rank' (Rank 1 through 15).
6. The index of the resulting DataFrame should be the name of the country, and the columns should be 'Citations per document', 'H index', 'Energy Supply', 'Energy Supply per Capita', '% Renewable', '2006', '2007', '2008', '2009', '2010', '2011', '2012', '2013', '2014', '2015'.
7. Analyze the data to answer some questions.

## Libraries Used

### We used the following libraries:

- pandas
- numpy

## Files

- Energy Indicators.xls
- world_bank.csv 
- scimagojr country rank 1996-2021.xlsx

