# Supermart Grocery Sales – Sales Performance & Forecasting

This project focuses on analyzing and modeling sales performance data for a fictional supermarket chain using a retail dataset. 
The goal was to not only explore and clean the data, but also to engineer new features that improve model accuracy and lead to meaningful business insights.

## Project Background

The default dataset lacked useful predictive power with the given features, so I decided to enhance it by creating custom columns that capture trends, seasonality, and performance indicators more effectively.
This approach helped me move beyond basic EDA into more refined modeling, and the improvements were reflected in the evaluation scores after feature engineering.


### 1. Data Understanding & Initial Cleaning
- Identified missing or inconsistent entries
- Removed irrelevant or low-variance features
- Handled categorical and date/time formatting issues

### 2. Feature Engineering
Since the original dataset didn’t provide many useful signals for modeling, I created several new features to uncover deeper patterns, including:

- **Sales category bins** based on performance tiers
- **Custom time-based columns** (e.g., month, quarter, weekday)
- **Profit ratio**, **cost-to-sales**, and other derived KPIs

These new features significantly improved the model's ability to generalize.
### 3. Exploratory Data Analysis
- Distribution of sales across cities, product types, and time periods
- Seasonal sales trends and weekday effects
- Correlations between new features and target variables

### 4. Modeling & Evaluation
- Trained regression models to forecast sales
- Compared model performance before and after adding engineered features
- Achieved improved scores by reducing error metrics after transformation

## Tools & Libraries Used
- Python (Pandas, NumPy)
- Matplotlib, Seaborn for visualization
- Scikit-learn for modeling and evaluation
- Jupyter Notebook

## Key Insights
- Cities with higher profit margins don't always have the highest total sales
- Product categories respond differently to time-based effects like holidays and weekends
- Custom KPIs like profit-to-cost ratio provided clearer signals for forecasting

## Why This Project Matters
Retail businesses depend heavily on accurate forecasting. Through careful preprocessing, new feature creation, and clear visual storytelling, this project shows how to turn a generic dataset into a decision-support tool with real-world relevance.

## Files Included
- `SUPERMART_GROCERY_SALES_PROJECT.ipynb`: Full notebook with data analysis, feature engineering, modeling, and results
- (Dataset file name if uploaded separately)

## Created by
Sriman Potthula  
Data Analyst in training | Python | EDA | Feature Engineering | Modeling
