# Used Car Price Prediction

Used car price prediction with linear, polynomial, Ridge and Lasso regression.

## What it does

Cleans a used car listings dataset (price, mileage and clean-title fields stored as text, missing fuel type and accident data), explores it, and compares regression models.

## Files

- `car_price_prediction.ipynb`
- `car_price_prediction_v2.ipynb`

## Tools

pandas, numpy, scikit-learn, Plotly, seaborn, matplotlib

## Dataset

[Used Car Price Prediction Dataset (Kaggle)](https://www.kaggle.com/datasets/taeefnajib/used-car-price-prediction-dataset)

The dataset is not included in this repo.

## Results

From the saved notebook outputs:

Linear Regression test MAE 8,341.87, RMSE 12,904.56. Polynomial (degree 2) test MAE 7,582.82, RMSE 11,202.62. Ridge and Lasso land close to the polynomial result.

## How to run

1. Open the notebook in Google Colab or Jupyter.
2. Install dependencies: `pip install -r requirements.txt`.
3. Download the dataset from the link above (some notebooks fetch it with `kagglehub`, which asks for Kaggle credentials) and update the data path if needed.
4. Run all cells.

## Author

Mark Ayman
