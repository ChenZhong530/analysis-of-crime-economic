# analysis-of-crime-economic
# Probelm & user: 
This project explores the relationship between crime rates and key economic/social factors across countries, aiming to identify the strongest drivers of crime risk and provide data-backed insights for policymakes and researchers.
# Data: 
Source: Crime Economics – data.csv (country-level socioeconomic and crime data); 
Access data: 2026.04.20;
Key fields: Country: Country name；Crime Rate: Target variable (overall crime rate)Unemployment (%), HDI, Per Capita Income, Gini Coefficient, Literacy Rate, Happiness Index,Weapons per 100 persons, Population Density Derived indicators: Total_Crime_Rate, Crime_Per_Happiness, Crime_Per_Literacy, Crime_Density, Crime_vs_Income
# Methods:
1.Removed duplicate rows and missing values
Converted columns to numeric format, filtered invalid outliers (negative values)
Final cleaned dataset: 109 rows × 13 columns
2.Feature Engineering:
Created derived crime metrics (crime rate adjusted for happiness index, literacy rate, income, and population density)
3.Exploratory Analysis:
Correlation heatmap to identify relationships between crime rate and socioeconomic variables
Scatter plots to visualize crime rate vs. unemployment, literacy rate, and weapons ownership
Bar chart of top 10 countries by crime rate
# Key findinds
There is a strong negative correlation (-0.65) between per capita income and crime rate: countries with higher average income tend to have significantly lower crime rates.
Crime rate shows a moderate negative correlation (-0.53) with HDI, indicating higher human development is linked to reduced crime risk.
Gini coefficient (income inequality) has a moderate positive correlation (0.48) with crime rate, suggesting inequality may drive higher crime levels.
Literacy rate shows a negative correlation (-0.36) with crime rate, though the relationship is less pronounced than income or HDI.
Unemployment rate shows only a weak positive correlation (0.15) with crime rate, meaning it is not a primary driver in this dataset.
# How to run 
# Product Link
# Limitation & next steps
Limitations: 
The dataset includes missing values for some variables (e.g., Per Capita Income), which required dropping incomplete rows
Correlation does not equal causation; external factors like culture, governance, and law enforcement are not included
Data is cross-sectional, so we cannot observe how crime and economic factors change over time
Next Steps:
Add time-series data to analyze trends over years
Include additional variables like governance quality, education spending, and law enforcement budget
Build a predictive model to estimate crime risk based on socioeconomic indicators
