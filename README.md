# Crime-Data-Analysis

Project Overview
This project involves the analysis of crime data from the official U.S. government repository, which spans from 2020 to the present. The goal of the analysis is to uncover insights into crime patterns, trends, and correlations across different regions and time periods. We explore various data preprocessing, cleaning, and exploratory data analysis (EDA) techniques, followed by predictive modeling to forecast future crime trends.

Data Source
The dataset used in this project is publicly available on Data.gov([Dataset](https://catalog.data.gov/dataset/crime-data-from-2020-to-present) It provides detailed information on crime incidents, including:

Dates and Times of occurrences
Geographical Information (LAT, LON, location details)
Crime Types and Descriptions
Victim Information (Age, Sex, Descent)
Weapon Information
We conducted data cleaning, handling of missing values, and encoding of categorical variables to prepare the dataset for analysis.

Project Components
Data Cleaning and Preparation: Handling missing data, removing redundant columns, and encoding categorical variables.
Exploratory Data Analysis (EDA):
Overall Crime Trends: Annual crime counts and variations from 2020 to 2023.
Seasonal Patterns: Crime rates analyzed across months and seasons.
Common Crime Types: Identification of the top crime categories, including "Vehicle Stolen" and "Battery - Simple Assault."
Regional Differences: Comparison of crime rates across regions within Los Angeles.
Correlation Analysis: Investigation into relationships between crime rates and socioeconomic factors such as unemployment rates.
Day of the Week Patterns: Analysis of crime frequency by day, highlighting trends for specific crime types.
Predictive Modeling: Use of time series forecasting (SARIMAX) to predict future crime trends.
Key Findings
Highest Crime Year: 2022 had the highest number of reported crimes, followed by a decline in 2023.
Seasonal Trends: Crimes tend to peak in the summer months (June to August).
Most Common Crime: "Vehicle Stolen" was consistently the top crime throughout the dataset.
Regional Differences: Central and 77th Street regions have the highest crime rates, while Foothill and Hollenbeck have the lowest.
Day of the Week: Crime occurrences peaked on Fridays, with Saturdays following closely behind.
Correlation with Unemployment: There was no significant correlation between unemployment rates and overall crime rates.
Tools and Technologies
Python (pandas, NumPy, matplotlib, seaborn)
Jupyter Notebook for interactive data analysis
Time Series Forecasting with SARIMAX model
Data Cleaning: Handling missing values, encoding categorical variables, data transformation
Visualization: Plotting trends and patterns using matplotlib and seaborn
