# Car-Prices-Prediction
This project uses regression models to predict car prices based on various vehicle features. The goal is to build an accurate, interpretable model that can assist in price estimation within the automotive market.

## Summary

- Explored dataset with vehicle attributes such as mileage, cylinders, liters, and cruise control
- Performed data cleaning, EDA, and feature engineering
- Built baseline Linear Regression model (R² = -0.167)
- Applied one-hot encoding to include categorical features (Make, Trim)
- Improved model performance to R² = 0.97

##  Techniques Used

- Linear Regression
- Ridge & Lasso Regression
- ElasticNet (with tuning)
- One-Hot Encoding
- Model Evaluation (RMSE, MAE, R²)

## Key Results

- Final model achieved **R² = 0.97**
- Ridge and Lasso performed comparably (R² ≈ 0.96–0.97)
- ElasticNet underperformed due to hyperparameter sensitivity
- Categorical feature inclusion was crucial for boosting accuracy

## Files Included

- `Regression - Predicting Car Prices.ipynb`: Full modeling workflow
- `cars.xls`: Original dataset
- `README.md`: Project overview and results summary

##  Tools & Libraries

`Python`, `Pandas`, `NumPy`, `Matplotlib`, `Scikit-learn`

## Future Improvements

- Try tree-based models (Random Forest, XGBoost)
- Cross-validation and hyperparameter tuning
- Incorporate more granular car features or external datasets
