# Zomato Restaurant Analysis

## Overview
This project analyzes the Zomato restaurant dataset to predict aggregate ratings using machine learning models, providing insights for business stakeholders and customers on restaurant selection and market trends.

## Project Details
- **Dataset:** Zomato restaurant data (12,000+ records covering cuisines, ratings, costs, and locations)
- **Technologies:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn
- **Performance:** Random Forest achieved R² = 0.87 for rating predictions

## Features
- Exploratory Data Analysis (EDA) on restaurant features like cuisines, city distributions, ratings, and cost correlations.
- Model training with Linear Regression, Random Forest, and Decision Tree Regression on an 80/20 train-test split.
- Evaluation using R² scores and visualizations for feature importance and market insights.

## Usage
- Run the Jupyter notebook `Zomato Restaurant Analysis.ipynb` to perform EDA, train models, and generate visualizations.
- Customize features or models in the code for different datasets.

## Results
- Random Forest outperformed with R² = 0.87, highlighting key predictors like votes and cost for restaurant ratings.
- Insights include top cuisines, rating patterns, and recommendations for improving ordering decisions.

## Challenges
- Handled categorical encoding (one-hot for cuisines/cities) and multicollinearity in features.
- Addressed dataset imbalances in ratings through model selection and cross-validation.

## Future Improvements
- Incorporate geospatial analysis for location-based insights.
- Add deployment via Streamlit for interactive restaurant recommendations.

## Contact
- Author: Yeshwanth Bikkavolu
- Email: yeswanthbikkavolu@gmail.com
- LinkedIn: linkedin.com/in/naga-veera-y-29379a2ba
