# Demand Forecasting and Procurement Planning

## Overview
This project is focused on creating an intelligent **demand forecasting** and **procurement planning** system for optimizing supply chain operations. By forecasting product demand, the system helps businesses make data-driven decisions to optimize procurement processes and ensure that the right amount of products are purchased at the right time. The goal is to reduce stockouts, minimize overstock, and optimize inventory levels for businesses.

## Objective
The objective of this project is to:
1. Predict future product demand using historical sales data.
2. Build a model for procurement planning that can suggest optimal order quantities and timing.
3. Utilize **time-series forecasting** techniques and **machine learning** models to generate demand forecasts.
4. Optimize inventory levels to reduce holding costs and avoid stockouts.

## Key Features
- **Demand Forecasting**: Predicts the future demand of products using time-series analysis, such as **ARIMA**, **Prophet**, or **LSTM** models.
- **Procurement Planning**: Suggests optimal procurement schedules, taking into account forecasted demand and current stock levels.
- **Visualization**: Graphs demand predictions, stock levels, and procurement suggestions.
- **Inventory Management**: Optimizes inventory levels to minimize holding costs and stockouts.

## Technologies Used
- **Python 3.x**
- **pandas**: For data handling and manipulation.
- **numpy**: For numerical computations.
- **matplotlib / seaborn**: For visualizations.
- **statsmodels**: For time series modeling (ARIMA, SARIMA).
- **Prophet**: For forecasting.
- **sklearn**: For machine learning models.
- **flask**: For deploying the solution as a web app (optional).

## Installation
Follow these steps to get the project running on your local machine:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/demand-forecasting-procurement.git
    cd demand-forecasting-procurement
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. To start using the application, run the `main.py` script (or the respective script for demand forecasting):
    ```bash
    python main.py
    ```

## Usage
The system works by taking in historical sales data (which can be in CSV or Excel format), then applying time-series forecasting methods to predict future product demand. Based on the predicted demand, the system then suggests procurement orders based on the **Economic Order Quantity (EOQ)** and inventory levels.

### Key Steps:
1. **Import Historical Data**: Load your historical sales data (e.g., `sales_data.csv`).
2. **Demand Forecasting**: Run time-series forecasting models (ARIMA, Prophet, LSTM) to predict demand.
3. **Procurement Recommendations**: The system calculates the procurement plan based on forecasted demand.
4. **Visualization**: View demand predictions and procurement recommendations in graphical formats.

```bash
python forecast_demand.py
