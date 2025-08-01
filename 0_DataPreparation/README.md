# Data Import and Preparation

Efficient and accurate data preparation is fundamental for successful forecasting models. The task includes importing the dataset into VS Code, cleaning it, and constructing new variables that are pertinent to forecasting sales.

## Contents

- **Data Importing**: We were given sales, weather and Kieler Woche festival dates. We added economic indicators, additional weather data to fill missing values, and the dates of public and school holidays.

- **Merging Data from different sources**: Several steps of merging are carried out in chapter 1.2.

- **Data Cleaning**: This task consists of finding missing or erroneous data, which belongs to the dataset characteristics.

- **Handling Missing Values**: This is also documented in chapter 1.2.

- **Constructing New Variables**: Several additional features are added in chapter 2: weather categorisation, day of the week and weekend, public and school holidays, and a "residual" category to separate oddities in the data.

- **Data Transformation**: Encoding of strings is carried out in chapter 3.1 to ensure that all values are numerical.

## Conclusion

This notebook results in a CSV file that provides both the Linear Regression baseline model and the Neural Network model with a dataset they can well work with.
