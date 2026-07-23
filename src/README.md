# Source Code

This folder contains the Python implementation of the Supply Chain Demand Forecasting project.

## Files

### 🐍 supply_chain_forecasting.py

Main implementation of the forecasting pipeline, including:

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Weekly demand aggregation
- Time series forecasting
- Model implementation
  - Naive Seasonal
  - Holt-Winters Exponential Smoothing (ETS)
  - MSTL + ETS
- Model evaluation using MAE and SMAPE
- Future demand prediction
- Forecast visualization

## Workflow

1. Load and preprocess the Walmart M5 dataset.
2. Perform exploratory data analysis to identify trends and seasonality.
3. Aggregate daily sales into weekly demand.
4. Train and evaluate multiple forecasting models.
5. Compare model performance using MAE and SMAPE.
6. Generate future demand forecasts for inventory planning.
7. Export forecast results and visualizations.

---

The source code demonstrates the complete machine learning pipeline used for demand forecasting and supports the findings presented in the Project Report and Project Presentation.
