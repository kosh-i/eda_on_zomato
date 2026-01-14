# eda_on_zomato
Exploratory Data Analysis on Zomato data 
# Zomato Restaurant Data Analysis

## Problem Statement
Zomato hosts thousands of restaurant listings with varying cuisines, pricing, and service options.
This project analyzes restaurant data to uncover trends related to ratings, cost, location,
and online ordering behavior.

## Dataset
- Source: Kaggle (Zomato Restaurant Dataset)
- Records: ~7,100 restaurants
- Features include restaurant type, rating, cost, cuisines, area, online order, and table booking

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Data Cleaning Steps
- Removed unnecessary index columns
- Standardized column names using snake_case
- Converted ratings and cost to numeric formats
- Handled missing values using median imputation
- Encoded categorical variables (Yes/No)

## Exploratory Data Analysis
Key analyses performed:
- Distribution of restaurant types
- Rating and cost distributions
- Impact of online ordering on ratings
- Relationship between cost and ratings
- Area-wise restaurant concentration
- Popular cuisines analysis

## Key Insights
- Quick Bite restaurants dominate the platform, indicating a delivery-first market.
- Most restaurants have ratings between 3.0 and 4.0.
- Higher cost does not necessarily result in better ratings.
- Restaurants offering online ordering tend to receive slightly higher ratings.
- Table booking is more common among higher-cost restaurants.
- Certain areas have significantly higher restaurant density.

## Conclusion
This analysis highlights consumer preferences and operational patterns on Zomato.
The insights can help restaurants optimize pricing, service offerings, and location strategy.

## Future Work
- Predict restaurant ratings using machine learning
- Location-based recommendation system
- Cuisine popularity forecasting

