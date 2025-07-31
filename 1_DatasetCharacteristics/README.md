# Dataset Characteristics

This part of the repository contains three Jupyter Notebooks focused on exploring and engineering features related to weather, time, and economy in order to understand their impact on sales.

## Project Goal

The main objective of this analysis is to **explore the dataset** and continuously assess **which external and internal factors influence sales**. Feature engineering is combined with exploratory data analysis to inform model development.

## Notebooks Overview

### 1. `sales.ipynb`
- Explores the relationship between sales and various influencing factors such as:
  - **Time variables** (e.g., weekdays, holidays)
  - **Weather indicators**
  - **Macroeconomic data** like **CPI**, **unemployment**, and **GDP**
- Uses plots and descriptive statistics to examine correlations and trends.
- Provides the foundation for identifying relevant feature groups.

### 2. `weather_code_and_wind.ipynb`
- Creates categorical groupings for various weather dimensions:
  - Weather condition codes → grouped into high-level weather types
  - Temperature → categorized into temperature classes
  - Wind speed → classified into wind strength levels
- Converts continuous raw weather data into interpretable, model-ready classes.

### 3. `weather.ipynb`
- Investigates the effect of different weather-related variables on sales performance.
- Analyzes how temperature, rainfall, wind, and other conditions impact sales behavior.
- Uses groupings and visualizations to highlight relationships.

## Summary

These notebooks form a comprehensive toolkit for understanding which external factors drive sales trends. They support both exploratory analysis and practical feature engineering for modeling purposes.
