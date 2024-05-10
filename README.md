# Data Mining Second Project

## Overview
This project involves the application of data mining techniques on a dataset to extract meaningful insights. The project is divided into two main parts:
1. Regression Analysis
2. Association Rule Mining

### Part 1: Regression Analysis
In the first part of the project, regression analysis is conducted to predict house prices based on various features such as age, distance to the nearest MRT station, number of convenience stores, latitude, and longitude. The dataset used contains multiple entries with details about different houses.

### Part 2: Association Rule Mining
The second part of the project utilizes the Apriori and FP-Growth algorithms to find frequent itemsets and generate association rules from a boolean dataset. This helps in discovering interesting relationships between different items.

## Implementation Details

### Regression Analysis
- The dataset is first loaded and preprocessed.
- Various regression models including Lasso, Ridge, Linear, Polynomial, Elastic Net, and XGBoost are employed to predict house prices using property-related features.

### Association Rule Mining
- The dataset is converted into a boolean format suitable for applying the Apriori and FP-Growth algorithms.
- Frequent itemsets are generated using both algorithms with specified support thresholds.
- Association rules are then derived from these itemsets with a confidence threshold to filter the most significant rules.
- The rules are visualized using scatter plots to depict the support and confidence of each rule.
