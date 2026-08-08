# Week 3: IPL Win Probability Predictor

## Overview
Developed an end-to-end Machine Learning model to predict the winning probability of second-inning IPL matches based on live match dynamics.

## Key Features & Workflow
- **Data Preprocessing:** Cleaned match and delivery datasets, calculated current score, target runs, runs left, balls left, and remaining wickets.
- **Feature Engineering:** Extracted `Current Run Rate (CRR)` and `Required Run Rate (RRR)`.
- **Pipeline & Model Training:** Used `ColumnTransformer` with `OneHotEncoder` for categorical variables (`batting_team`, `bowling_team`, `city`) and trained a `LogisticRegression` classifier.
- **Match Progression Visualization:** Simulated over-by-over win/loss probability changes using `matplotlib`.
- **Model Export:** Serialized the trained pipeline model to `pipe.pkl`.