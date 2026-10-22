# House Price Prediction

Predicts house prices in California using two regression models.

- **Dataset:** California Housing (from scikit-learn)
- **Models:** Linear Regression and Random Forest
- **Results:**

| Model | R2 score | Mean absolute error |
|---|---|---|
| Linear Regression | 0.576 | 0.533 |
| Random Forest | 0.805 | 0.328 |

- **Conclusion:** Random Forest predicts prices much more accurately than Linear Regression.

## Key Finding
Feature importance (Random Forest) shows that median income of the area is the strongest predictor of house price (52.5%), followed by average occupancy (13.8%) and location (latitude and longitude, 8.9% each).

## How to run
Open `House_price.ipynb` in Google Colab and click Run all.
