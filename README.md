# UberEats Food Preferences and Pricing Analysis

## Project Overview
This project aims to uncover the dining preferences and pricing patterns among users of the UberEats platform across different states and cities in the United States. By analyzing a dataset encompassing restaurant offerings and their menu items, the study provides insights into the most popular food categories, specific popular dishes, and their corresponding prices.

## Key Questions Addressed
- What are the most frequently ordered food categories in each state and city?
- Which specific food items are favored in various locales?
- How do the prices of popular food items compare across different regions?

## Methodology
The analysis process encompassed several stages:
1. **Data Cleaning and Preprocessing**: Standardized the `price` column to a numeric format and extracted the `state` and `city` information from the `full_address` column. Then combined rows in the dataset where food items had the same name and category but were listed on different rows to ensure accurate average prices and item counts.

2. **Exploratory Data Analysis (EDA)**: The goal of EDA here was to identify the distribution of restaurants, the most popular food categories, and the average prices for these categories across different states and cities.

3. **Data Visualization**: Created a series of bar graphs to visualize the most popular food categories and their average prices in each state.

4. **Most Popular Foods (+Prices) Per City/State**: Created a function that generates a dataframe the contains the most popular foods and their average prices for any desired state or city.

## Findings
The project revealed interesting patterns such as the prevalence of 'Picked for you' recommendations, the popularity of beverages and sides, and regional pricing similarities.
