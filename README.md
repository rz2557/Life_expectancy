# Life Expectancy Prediction

What drives life expectancy across countries? This project models life expectancy on the WHO health and socioeconomic dataset and compares regression models.

## Approach

1. **Explore** the data: distributions, missing values and relationships between health, immunization, mortality and socioeconomic variables.
2. **Prepare** the features: feature engineering and reducing multicollinearity so coefficients and importances are interpretable.
3. **Model** life expectancy with several regression models, including gradient boosting, and compare them with baselines.
4. **Interpret** the results with variable-importance, trend and residual plots (Seaborn and Matplotlib).

## Results

Gradient boosting performed best, reaching an R² of about 0.89 and outperforming the baseline models. See the notebook for the full comparison and plots.

## Files

| File | Description |
|---|---|
| `Life_expectancy_project.ipynb` | Full analysis |
| `Life Expectancy Data.csv` | WHO life expectancy dataset |

## Tech

Python, pandas, scikit-learn, Seaborn, Matplotlib. Open the notebook in Jupyter or Google Colab.
