---
layout: single
title: "Baseball Analytics"
permalink: /baseball/
---

## MLB Pitcher Strikeout Projection

A machine learning project focused on predicting future MLB pitcher strikeout rate using previous-season performance, Stuff+, workload, and age.

The project examines how persistent strikeout rate is from season to season and whether incorporating Stuff+, workload, and age can improve predictions over a simple previous-season K% baseline.

**Methods:** R, Random Forest, Linear Regression, chronological validation

[View the project on GitHub](https://github.com/eimioda/mlb-pitcher-strikeout-projection)

---

## MLB Pitching Performance Analysis

An analysis of MLB Statcast data examining pitching performance, stability, and predictive value across multiple seasons.

The project looks at metrics including K%, GB%, K-BB%, BABIP, and HR/FB, as well as pitch usage by hitter handedness and pitch count.

**Methods:** R, baseballr, tidyverse, ggplot2

[View the project on GitHub](https://github.com/eimioda/mlb_pitching_performance_analysis)

---

## Baseball Analytics Data Pipeline

A data pipeline project focused on collecting, transforming, and querying MLB performance and salary data.
The project includes a SQLite relational database and SQL queries for player filtering, leaderboard analysis, and performance exploration. An interactive Streamlit dashboard integrates a linear regression model to generate salary predictions from player performance metrics.

**Methods:** Python, SQL, SQLite, ETL, Streamlit

[View the project on GitHub](https://github.com/eimioda/baseball-etl-pipeline)

---

## MLB Salary Prediction Using Machine Learning

A machine learning project focused on predicting MLB player salaries from historical batting performance data.

The project compares Lasso Regression, Random Forest, and k-Nearest Neighbors models, with preprocessing and feature engineering including dataset merging, missing-value imputation, and log transformation of salary distributions.

Models were evaluated using RMSE with K-fold cross-validation and GridSearchCV, with feature importance analysis used to identify key predictors of player salary.

**Methods:** Python, Scikit-learn, Lasso Regression, Random Forest, k-Nearest Neighbors

[View the project on GitHub](https://github.com/eimioda/mlb-salary-prediction)

