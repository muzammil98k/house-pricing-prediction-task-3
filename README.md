# Linear Regression on Housing Dataset

## Project Steps

1. Import and preprocess dataset (`Housing.csv`).
2. Split into train-test sets.
3. Train Linear Regression model.
4. Evaluate model using MAE, MSE, R².
5. Plot regression line (`area` vs `price`) and interpret coefficients.

## Requirements

```bash
pip install pandas scikit-learn matplotlib
```

## Results

* MAE: ~9.7 Lakhs
* R²: ~0.65
* Coefficient (Area): ~425 (each unit area adds ~₹426).
* Intercept: ~₹25,12,254.

## Run

```bash
jupyter notebook Linear_Regression_Housing.ipynb
```
