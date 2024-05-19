# TMDB Movie Analysis

This repository contains an analysis of the TMDB movie dataset available on Kaggle. The analysis includes data cleaning, exploratory data analysis (EDA), and model fitting to the dataset. There are two main procedures involved: one in the main branch focusing on simple EDA and data cleaning, and another in the `merg_df` branch where more advanced data cleaning, EDA, and regression/classification modeling are performed. The name of the `merg_df` branch suggests that two datasets have been merged into a single dataset.

## Analysis Overview

In this analysis, the following tasks have been undertaken:

- **Data Cleaning**: Initial cleaning of the dataset to handle missing values, inconsistencies, and outliers.
- **EDA**: Exploratory Data Analysis to gain insights into the dataset. This includes understanding the general relationships between features, exploring features such as year of release, profit of the movie, popular release days, duration effects on profits and popularity, genre distribution, and revenue trends over the years.
- **Modeling**: Fitting regression and classification models to forecast movie revenue and profitability.

## Key Insights

The analysis provides insights into various aspects of the dataset, including:

- General relationships between features.
- Insights on features such as year of release and movie profitability.
- Identification of the most profitable release days in terms of popularity and profit.
- Analysis of how movie duration affects profitability, voting average, and popularity over the years.
- Linear correlations between revenue and other factors such as budget, popularity, and vote count.
- Identification of the most common genres.
- Trends in movie revenue over the years.

## Packages Used

The analysis utilizes the following Python packages:

- Pandas
- Seaborn
- Scikit-learn
- Matplotlib
- NumPy

## Dataset

The TMDB movie dataset used in this analysis can be found on Kaggle [here](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata/data).

## Repository Structure

- **main**: Contains the main analysis code focusing on simple EDA and data cleaning.
- **merg_df**: Contains advanced data cleaning, EDA, and regression/classification modeling.


