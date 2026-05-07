# 🏆 WorldCup Match Predictor

ML classification model predicting FIFA World Cup match outcomes (win/draw/loss) from 152 years of international football data.

## Overview

This project builds a supervised machine learning pipeline to predict the outcome of international football matches — **Home Win**, **Away Win**, or **Draw** — using historical match data from 1872 to 2024.

The goal is to apply this model to predict match outcomes for the **2026 FIFA World Cup**.

## Dataset

- **Source:** [Global Football Results 1872–2024](https://www.kaggle.com/datasets/muhammadehsan02/global-football-results-18722024) — Kaggle
- **Size:** 47,399 international matches
- **Features used:** Home team, Away team, Tournament type, Neutral ground

## Project Pipeline

```
Load Data → Exploratory Analysis → Feature Engineering → Encoding → Train/Test Split → Model Training → Evaluation → Optimization
```

## Models Compared

| Model | Type |
|-------|------|
| Logistic Regression | Baseline classifier |
| Random Forest | Ensemble method |
| XGBoost | Gradient boosting |

## Tech Stack

- **Python** — Pandas, NumPy, scikit-learn, XGBoost
- **Visualization** — Matplotlib, Seaborn
- **Environment** — Jupyter Notebook

## Results

*In progress — models being trained and evaluated.*

## Author

**Walid Hamdoune** — Data Science Student @ Concordia University  
[LinkedIn](https://linkedin.com/in/walidhamdoune) | [GitHub](https://github.com/WalidHamdoune)
