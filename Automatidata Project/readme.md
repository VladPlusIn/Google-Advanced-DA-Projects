# Taxi Fare Prediction Project

This project aims to predict taxi fares in New York City based on various features related to taxi trips, such as distance, time, locations, and payment type. The dataset used for this analysis comprises taxi trip data from 2017, including details like pickup/dropoff times, locations, fare amount, trip distance, payment type, and more.

## Overview
The project workflow covers several stages:

### Data Exploration and Cleaning
- Initial analysis of the dataset to understand its structure and properties.
- Handling missing values, data type conversions, and exploratory data analysis (EDA).

### Visualization and Insights
- Visualizations showcasing trip distances, fare amounts, tip amounts, rides by month/day, and total revenue by month/day.
- Analysis of passenger counts influence on tip amounts.

### Hypothesis Testing
- Conducting an A/B test to determine the difference in average fare between credit card and cash payments.
- Insights derived from the hypothesis test.

### Imputation and Outlier Handling
- Addressing zero trip distances and handling fare amount outliers.
- Handling duration outliers and imputing maximum values.

### Feature Engineering
- Creating new features like mean distance and mean duration based on pickup and dropoff locations.
- Generating day, month, and rush hour features for analysis.

### Model Building and Evaluation
- Using Linear Regression to predict fare amounts.
- Pre-processing, scaling, and splitting data into training and testing sets.
- Model evaluation metrics and residual analysis.

## Contents
The project repository includes the following files:
- **Jupyter Notebook**: Contains the code and step-by-step analysis of the project.
- **CSV Data File**: Original dataset used for analysis.
- **README.md**: Markdown file explaining the project overview, steps, and findings.

## Usage
To replicate or run this project locally, follow these steps:
1. Clone the repository to your local machine.
2. Ensure you have the necessary dependencies installed (Python, Jupyter, libraries like Pandas, Matplotlib, Seaborn, Scikit-learn).
3. Open the Jupyter Notebook and run each cell in sequence to replicate the analysis.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Findings
- Predictive model to estimate taxi fares performs with an R2 score of 0.868 on the test set.
- The distribution of residuals is approximately normal, suggesting the model's errors are unbiased.

## Acknowledgments
- The dataset used in this project is sourced from the New York City Taxi and Limousine Commission (TLC).
- Acknowledgment to libraries and resources used for analysis and visualization.
