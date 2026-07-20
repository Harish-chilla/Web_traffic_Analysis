
# Web Traffic Analysis and Prediction

## Overview

This project analyzes website traffic and user engagement data to identify the factors that influence total estimated website visits. Exploratory data analysis and machine learning techniques are used to understand traffic patterns and build a predictive model.

The project demonstrates an end-to-end data analysis workflow, including data exploration, feature analysis, visualization, model development, and evaluation.

## Objective

The main objectives of this project are to:

- Analyze website traffic and user engagement patterns.
- Identify important factors influencing estimated website visits.
- Explore relationships between user activity and website traffic.
- Build a machine learning model to predict total estimated visits.
- Evaluate the performance of the predictive model using regression metrics.

## Dataset

The dataset contains 10,000 records of website traffic and user engagement data.

### Features

| Feature | Description |
|---|---|
| Year | Year of the observation |
| Month | Month of the observation |
| Active_Logged_In_Users | Number of active logged-in users |
| Unique_Users_Rating | Number of unique users who submitted ratings |
| Total_Ratings_Submitted | Total number of ratings submitted |
| Total_Page_Views | Total number of page views |
| Avg_Session_Duration_Sec | Average user session duration in seconds |

### Target Variable

- `Total_Estimated_Visits` – The estimated number of total website visits.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Loading

The dataset was loaded into Python using Pandas.

### 2. Exploratory Data Analysis

The dataset was explored to understand:

- Data structure
- Feature distributions
- Relationships between variables
- Correlations between user engagement metrics and website visits

### 3. Data Analysis and Visualization

Visualizations were created to analyze:

- Website traffic trends
- User engagement patterns
- Correlations between variables
- Feature importance

### 4. Machine Learning Model

A Random Forest Regression model was developed to predict `Total_Estimated_Visits`.

### 5. Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Results

The Random Forest Regression model achieved:

- **R² Score: 0.9886**
- **MAE: 4,916,775.15 visits**
- **RMSE: 6,270,133.72 visits**

The results indicate that the model was able to explain a significant proportion of the variation in estimated website visits based on user engagement and traffic-related features.

## Key Insights

- User engagement metrics showed a strong relationship with estimated website visits.
- Page views and active users were important indicators of website traffic.
- Machine learning can be used to support traffic forecasting and data-driven decision-making.

## Project Structure

```text
Web-Traffic-Analysis/
│
├── web.ipynb
├── imdb_traffic.csv
└── README.md
