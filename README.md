# City_Power_Consumption_Analysis_and_Prediction
## Problem Statement
Accurate forecasting of power consumption is essential for efficient energy planning and resource optimization. This project analyzes city-level power consumption data to identify key influencing factors and build regression models to predict electricity usage in a specific zone.

## Dataset Overview
- Dataset contains numerical features related to city power usage across multiple zones
- Target variable: Power_Consumption_in_A_Zone
- Data sourced from an Excel file and prepared for analytical and predictive modeling

## Approach
- Loaded and cleaned the dataset by removing irrelevant columns and standardizing feature names.
- Handled missing values using median imputation for numerical stability.
- Conducted exploratory data analysis (EDA), including correlation analysis and visualization.
- Applied feature scaling using StandardScaler.
- Built and evaluated regression models to predict power consumption.

## Tools & Technologies
- Programming: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
- Machine Learning: Scikit-learn
- Techniques: EDA, feature scaling, regression modeling, model evaluation

## Model Development & Evaluation
- Implemented Linear Regression as a baseline model.
- Implemented Random Forest Regressor to capture non-linear relationships.
- Evaluated models using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score
- Model performance was compared to understand trade-offs between simplicity and predictive capability.

## Key Insights
- Identified strong correlations between multiple power-related features.
- Tree-based models demonstrated improved ability to capture complex relationships.
- Feature scaling significantly improved model stability for linear regression.

## Future Improvements
- Perform hyperparameter tuning to further optimize model performance.
- Experiment with additional regression algorithms.
- Explore time-based forecasting techniques if temporal data is available.
- Study deployment approaches using cloud platforms (learning phase).

## Learnings
- Strengthened understanding of regression-based ML workflows.
- Gained hands-on experience with data preprocessing, scaling, and evaluation.
- Improved ability to interpret model results in an energy analytics context.
