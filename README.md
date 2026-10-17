# NFL-Win-Prediction-Analysis
# Predicting NFL Game Outcomes Using Machine Learning

## Project Overview

This independent sports analytics project explores the relationship between NFL team statistics and winning, and investigates whether historical performance can predict future game outcomes.

Using Python, I analyzed NFL data from the 2015–2025 seasons and developed a logistic regression model to predict game outcomes.

## Research Question

Which NFL team statistics are most strongly associated with winning, and how accurately can recent team performance predict future NFL games?

## Methodology

- Collected and cleaned NFL team and game data.
- Analyzed turnover, rushing-yard, and passing-yard differentials.
- Created visualizations comparing statistical performance with winning percentages.
- Engineered pregame features using rolling averages from each team's previous five games.
- Trained a logistic regression model on 2015–2023 data.
- Evaluated predictions on 2024–2025 games.

## Key Results

| Metric | Result |
|---|---|
| Model accuracy | 63.50% |
| Baseline accuracy | 50.00% |
| Improvement | +13.50 percentage points |
| Unique test games | 537 |
| 2024 accuracy | 64.31% |
| 2025 accuracy | 62.69% |

### Main Findings

Turnover differential had the strongest observed relationship with winning among the three same-game statistics analyzed.

However, when predicting future games using recent performance, passing-yard and rushing-yard advantages had slightly larger standardized coefficients than turnover advantage.

These findings highlight the difference between explaining completed game outcomes and predicting future results.

## Technologies Used

- Python
- pandas and NumPy
- Matplotlib
- scikit-learn
- Google Colab
- nflreadpy

## Limitations

The model does not account for injuries, quarterback changes, home-field advantage, or strength of schedule. Its accuracy represents performance on the historical test set and does not guarantee future results.

## Project Notebook

[View the full analysis](NFL_Win_Prediction_Analysis_Organized.ipynb)
