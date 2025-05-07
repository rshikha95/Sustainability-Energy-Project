# Sustainability-Energy-Project
Analyzing building energy consumption data and predicting usage patterns.

# Predicting Household Electricity Consumption

## Overview and Goal

This project aims to analyze and predict household electricity consumption based on various factors such as national electricity demand, weather conditions (temperature, humidity, wind speed) and time-based features. The goal is to understand the key drivers of household energy usage and build a model to forecast consumption.

## Data Source

*   **Dataset:** [240,000+ Household Electricity Consumption Records](https://www.kaggle.com/datasets/thedevastator/240000-household-electricity-consumption-records) from Kaggle.
*   **Description:** This dataset contains time-series data including national electricity demand, weather variables and the target variable: household electricity consumption (`target`).
*   **File:** `household_power_consumption.csv`

## Tools Used

*   Python
*   Pandas (Data manipulation and analysis)
*   NumPy (Numerical operations)
*   Matplotlib  and Seaborn (Data visualization)
*   Scikit-learn (Machine learning model building and evaluation)
*   Jupyter Notebook (Development environment)
*   (Potentially SQLite for SQL practice)

## Analysis Steps

1.  **Data Loading and Initial Inspection:** Load the dataset and perform initial checks for data types, missing values, and basic statistics.
2.  **Data Cleaning:** Handle missing values, correct data types (especially `datetime`), and address any inconsistencies.
3.  **Exploratory Data Analysis (EDA):**
    *   Analyze the distribution of the target variable (household consumption).
    *   Explore trends over time (daily, weekly, monthly, seasonal patterns).
    *   Investigate correlations between household consumption and weather variables (temperature, humidity, wind).
    *   Compare household consumption patterns with national demand.
    *   Visualize relationships.
4.  **Feature Engineering:**
    *   Extract relevant features from the `datetime` column (e.g., hour, day of week, month, season).
    *   Consider creating lag features or interaction terms if appropriate.
5.  **Model Building:**
    *   Select appropriate regression models (e.g., Linear Regression, Random Forest Regressor, Gradient Boosting).
    *   Split data into training and testing sets.
    *   Train and evaluate models.
6.  **Model Evaluation & Interpretation:**
    *   Evaluate model performance using metrics like RMSE, MAE, R-squared.
    *   Analyze feature importance to understand key drivers.

## Key Findings / Visualizations



## Conclusions / Future Work



## How to Run (Optional - can be added later)

1.  Clone the repository.
2.  Ensure Python and necessary libraries are installed.
3.  Run the Jupyter Notebooks in the `notebooks/` directory.

