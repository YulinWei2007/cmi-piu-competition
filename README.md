# CMI PIU Competition — TabNet & Gradient Boosting

Kaggle notebook for the Child Mind Institute — Problematic Internet Use competition.

## Overview
This notebook builds on a public baseline and extends it with TabNet, combined with gradient boosting models (LightGBM, XGBoost, CatBoost) for the regression task.

## Approach
- **Data processing**: NumPy, Pandas, Polars for efficient handling of structured data
- **Modeling**: TabNet (deep learning for tabular data) blended with LightGBM / XGBoost / CatBoost
- **Visualization**: Matplotlib, Seaborn for EDA

## Results
- Private score: 0.426
- Best public leaderboard score: 0.435

## Based on
Adapted from [this public notebook](https://www.kaggle.com/code/honganzhu/cmi-piu-competition?scriptVersionId=201912528) (Version 44, LB 0.492).

## Files
- `lb0-494-with-tabnet.ipynb` — main notebook
