

# Sugarcane Production Analysis

This repository contains a Jupyter Notebook that performs an analysis of sugarcane production data using Python and popular data analysis libraries such as Pandas, Seaborn, and Matplotlib. The dataset used in this analysis is named "List of Countries by Sugarcane Production.csv."

### Setup
Before running the code in the notebook, make sure you have the required libraries installed. If you don't have them, you can install them using pip:

pip install pandas seaborn matplotlib

## Table of Contents

- [Description](#description)
- [Setup](#setup)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Univariate Analysis](#univariate-analysis)
- [Bivariate Analysis](#bivariate-analysis)
- [Correlation Analysis](#correlation-analysis)
- [Analysis by Continent](#analysis-by-continent)
- [Conclusion](#conclusion)

## Dataset

The dataset contains information about sugarcane production in various countries. It includes the following columns:

- `Country`: The name of the country.
- `Continent`: The continent where the country is located.
- `Production(Tons)`: Total sugarcane production in tons.
- `Production_per_person(Kg)`: Sugarcane production per person in kilograms.
- `Acreage(Hectare)`: Total acreage of land used for sugarcane cultivation in hectares.
- `Yield(Kg/Hectare)`: Yield of sugarcane in kilograms per hectare.

## Data Cleaning

The initial data cleaning steps include removing unwanted characters (e.g., commas, dots) from numeric columns and dropping irrelevant columns. The future warnings during data cleaning are acknowledged but not significant to the analysis.

## Univariate Analysis

The univariate analysis examines individual columns separately. It includes visualizations such as bar plots and distribution plots to understand the data distribution and identify outliers.

## Bivariate Analysis

The bivariate analysis explores the relationships between two variables, such as land area vs. total production and yield per hectare vs. total production. Scatterplots and bar plots are used to visualize these relationships.

## Correlation Analysis

The correlation analysis investigates the relationships between numerical variables. A heatmap is used to visualize the correlation matrix and identify any significant correlations.

## Analysis by Continent

The analysis is also conducted at the continent level to understand how production and other variables vary across different continents. Bar plots and line plots are used to visualize these comparisons.

## Conclusion

This analysis provides insights into sugarcane production across different countries and continents. It explores the relationship between various production-related metrics and uncovers patterns and trends within the dataset.

For more details, please refer to the Jupyter Notebook in this repository.
