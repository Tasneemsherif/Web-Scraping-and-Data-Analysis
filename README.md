# Web-Scraping-and-Data-Analysis

## Overview
In this project, I performed web scraping to extract information about technology companies in Egypt from a website. The data includes details such as revenue, customers, year founded, funding, and team size. After collecting the data, I cleaned and analyzed it using Python and pandas.

## Tools and Libraries Used
Python 3
Jupyter Notebook
Libraries:
NumPy
pandas
requests
BeautifulSoup
seaborn
matplotlib

## Data Collection
I utilized web scraping techniques to gather information from the website "https://getlatka.com/companies/countries/egypt". The extracted data includes company names, revenue, customers, year founded, funding, and team size.

## Data Cleaning
I performed data cleaning to handle missing values and convert data types. Specifically, I converted revenue values to numeric format, replaced missing values, and standardized funding values.

## Data Analysis
I conducted a preliminary analysis of the dataset, including basic statistics and visualizations. The analysis covers descriptive statistics for the 'team size' column, providing insights into the distribution of team sizes among the companies.

## Results
The cleaned and analyzed data is stored in a CSV file named "Egypt_companies_revenue.csv" or "data_set.csv" in the working directory.

## Insights
The average team size is approximately 95, with a wide range from 0 to 901.
The funding column includes a mix of numeric values and non-numeric values. Conversion and standardization were applied to handle this variation.

## Visualizations
I included visualizations using seaborn and matplotlib to illustrate aspects of the data, such as the distribution of team sizes among the companies.
