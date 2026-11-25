# Cocktail Demand Prediction

A machine learning regression project that predicts daily cocktail sales based on historical bar data, helping bar managers optimize prep work and inventory.

## Project Overview
- **Goal:** Predict daily `units_sold` for each cocktail on the menu.
- **Features Engineered:** `day_of_week`, `is_weekend` (Friday–Sunday rush indicator), `month`, and one-hot encoded `drink_name`.
- **Models Compared:** Linear Regression vs. Random Forest Regressor.
- **Evaluation Metrics:** Mean Absolute Error (MAE) and R-squared (R²), visualized with Actual vs. Predicted scatter plots.

## Project Structure
```text
cocktail-demand-prediction/
├── data/
│   └── cocktail_sales.csv
├── cocktail_demand_prediction.ipynb
├── .gitignore
└── README.md
```

## How to Run Locally
1. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
2. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter ipykernel
   ```
3. Open `cocktail_demand_prediction.ipynb` in VS Code or Jupyter and run all cells.
