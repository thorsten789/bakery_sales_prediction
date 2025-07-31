# Baseline Sales Forecasting Model

This notebook presents the development and evaluation of a baseline regression model for predicting sales based on structured external and internal features.

## Contents

- **Feature Import**: Uses preprocessed feature tables prepared in earlier steps.
- **Missing Data Check**: Ensures no missing values remain before modeling.
- **Time-Based Data Split**: Splits data into training, validation, and test sets chronologically.
- **Feature Group Testing**: Combines different feature groups (e.g., time, weather, product categories, economy) into multiple regression model formulas.
- **Model Training**: Fits OLS regression models using `statsmodels` to assess predictive power.
- **Evaluation**: Compares models based on R² score.

## Key Models

- `Model_AllCoreFeatures_WithResidual`: Chosen as the **baseline model**, balancing simplicity and strong performance.  
- `Model_AllFeatures_WithWeatherGroups_Residual`: Achieves slightly higher R² but with significantly more complexity.

## Conclusion

The baseline model is sufficient for capturing most of the variance in sales with interpretable and manageable feature complexity.