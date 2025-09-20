# Polynomial-Regression-Project-Age-Vs-Height-
# Polynomial Regression: Age vs Height

##  Project Goal
To model and predict a person's height based on their age using polynomial regression, and to determine the best-fitting polynomial degree that minimizes prediction error and generalizes well to unseen data.

## Dataset
The dataset contains observations of individuals' age and corresponding height. The goal is to understand the relationship between these two variables.

## Methodology
1. **Data Splitting**: The dataset is split into training and test sets (80/20 split).
2. **Polynomial Regression**: Models of degrees 1 to 4 are trained using `PolynomialFeatures` and `LinearRegression`.
3. **Evaluation**: Each model is evaluated using RMSE (Root Mean Squared Error) for both training and test sets.
4. **Visualization**: Scatter plots and prediction curves are generated to visually compare model performance.

##  Model Comparison
- Degree 1: Linear model
- Degree 2–4: Polynomial models with increasing flexibility
- RMSE values are printed for each degree to identify the best fit

##  Conclusion
The model with the lowest RMSE on the test set and minimal overfitting is selected as the best fit. Polynomial regression of degree 4 provided the most accurate predictions in this case.
