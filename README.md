### Predicting MEDV and NOX – Boston Housing Dataset

This project explores environmental and socioeconomic factors that influence two key variables in the Boston housing dataset:

- **MEDV** — Median value of owner-occupied homes
- **NOX** — Nitric oxide concentration (parts per 10 million)

Using correlation analysis and linear regression modeling, the notebooks identify the most influential features and evaluate model performance.

### Contents

- **`Predicting_MEDV.ipynb`**: Regression analysis is used to identify the best predictors of MEDV, including RM (average number of rooms) and LSTAT (lower-status population).
- **`Predicting_NOX.ipynb`**: Regression analysis is used to identify the best predictors of NOX, focusing on AGE (older buildings) and DIS (distance to employment centers).
- PDF exports are included for each notebook

### Tools & Libraries

- pandas, numpy
- seaborn, matplotlib
- statsmodels (OLS regression)

### Key Insights

- LSTAT and RM show the strongest relationships with MEDV
- AGE and DIS have significant predictive power for NOX
- All models are statistically significant with strong R² values

### Data Source

Boston Housing Dataset (originally from UCI, accessible via `data/boston.csv`)

### License

MIT License — see the `LICENSE` file for details.
