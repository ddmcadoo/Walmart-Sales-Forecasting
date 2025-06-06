# Walmart-Sales-Forecasting
This project analyzes and forecasts weekly sales data from Walmart stores. The goal is to identify trends, patterns, and build predictive models that help in decision-making related to demand planning and inventory management.

## Project Goals

- Analyze weekly sales data across stores.
- Visualize sales trends over time.
- Identify the impact of holidays and promotions.
- Forecast future sales using machine learning or statistical models.

## Dataset

- **Source**: [Walmart Sales Dataset](https://www.kaggle.com/datasets/yasserh/walmart-dataset) *(or update with your source)*.
- **Features**:
  - `Store`: Store number
  - `Date`: Weekly date
  - `Weekly_Sales`: Weekly sales for the store
  - `Holiday_Flag`: Whether the week includes a holiday
  - `Temperature`, `Fuel_Price`, `CPI`, `Unemployment`: External factors

## Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn 

## Key Findings

- Sales fluctuate seasonally, especially around holidays like Thanksgiving and Christmas.
- Certain stores consistently outperform others in total weekly sales.

## Next Steps

- Try advanced models: Prophet, or LSTM for time series forecasting.
- Perform hyperparameter tuning and cross-validation.
- Explore store-level predictions and granular holiday effects.
- Deploy the model as a Flask or Streamlit app for interactive sales forecasting.

## Author

Darion McAdoo  
[LinkedIn](https://www.linkedin.com/in/ddmcadoo) | [GitHub](https://github.com/ddmcadoo)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ddmcadoo/walmart-sales-forecasting.git
   cd walmart-sales-forecast
