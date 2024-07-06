# ML-Airbnb-Analysis

## Airbnb Price Prediction Project

### Overview

This project aims to help new Airbnb hosts in Dallas, Texas set competitive and profitable prices for their properties using data analysis and machine learning techniques. The goal is to predict optimal pricing based on key property features like number of bedrooms, type of room, minimum nights, and availability.

**Tools and Techniques Used**

- **Data Handling**: Pandas for data manipulation and cleaning.
- **Visualization**: Matplotlib and Seaborn for data visualization.
- **Machine Learning Models**: Linear Regression, Decision Tree Regression, Random Forest Regression, and XGBoost for predicting prices.

### Steps Taken

**Data Import and Cleaning:**

- Loaded Airbnb listing data from a CSV file.
- Selected relevant columns like accommodation details, room type, price, and availability.
- Cleaned data by removing special characters from price and handling missing values.

**Exploratory Data Analysis (EDA):**

- Visualized the distribution of numerical features such as accommodation capacity, bedrooms, and price.
- Identified outliers in price and removed them to improve model accuracy.

**Model Building and Evaluation:**

- **Multiple Regression**: Used for baseline prediction of prices.
- **Decision Tree Regression**: Captured complex relationships between features and prices.
- **Random Forest Regression**: Enhanced accuracy by averaging multiple decision trees.
- **XGBoost**: Boosted decision trees model for higher predictive power.

**Model Performance:**

- Evaluated each model using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), Mean Squared Error (MSE), and R-squared (R²).
- Found that the Decision Tree Regression model outperformed others, explaining up to 97.1% of the price variance.

**Feature Importance:**

- Determined that features like number of bedrooms, availability throughout the year, and accommodation capacity significantly influenced price predictions.
- Visualized feature importance using bar charts.

### Conclusion

The Decision Tree Regression model proved most effective for predicting Airbnb prices in Dallas. Future work could involve refining models, exploring additional features, or implementing more sophisticated algorithms to further enhance prediction accuracy.
