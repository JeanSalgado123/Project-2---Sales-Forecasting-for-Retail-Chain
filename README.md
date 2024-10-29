# Project-2: Retail Sales Forecasting

## Overview
This project aims to predict future sales for a retail store using historical sales data. The goal is to develop a forecasting model that helps in inventory planning, optimizing stock levels, and improving overall sales strategies.

## Objectives
- Analyze historical sales data to identify trends and seasonality.
- Use time series forecasting methods to predict future sales.
- Provide actionable insights to improve inventory management and sales strategies.

## Dataset
The dataset contains historical sales records, including daily sales, store information, promotional activities, and holiday events. It is assumed to be in CSV format and stored in the `data` folder.

## Methodology
1. **Data Collection:** Historical sales data is collected from retail store records.
2. **Data Cleaning:** Handle missing values and remove anomalies to ensure data accuracy.
3. **Exploratory Data Analysis (EDA):** Use statistical analysis and visualizations to understand sales trends, seasonality, and patterns.
4. **Modeling:** Implement time series forecasting models, such as ARIMA or Prophet, to predict future sales.
5. **Evaluation:** Evaluate model performance using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Requirements
To run this project, you need the following libraries installed:
```bash
pip install pandas matplotlib scikit-learn statsmodels fbprophet
```

## How to Run
1. Clone this repository: `git clone https://github.com/JeanSalgadoAI/Project-2---Retail-Sales-Forecasting.git`
2. Navigate to the project folder: `cd Project-2---Retail-Sales-Forecasting`
3. Ensure that the dataset is in the `data` folder.
4. Run the Jupyter Notebook: `jupyter notebook notebooks/Sales_Forecasting.ipynb`

## Results
- The forecasted sales are visualized using line plots, highlighting trends and seasonality.
- The model performance is evaluated using MAE and RMSE, and results are provided in the final report.

## Files and Folders
```bash
Project-2---Retail-Sales-Forecasting
│   README.md
│   LICENSE
│   .gitignore
│
├───data
│    └── raw (contains raw data files)
│
├───models
│    └── sales_forecast_model.pkl (contains trained model)
│
├───notebooks
│    └── Sales_Forecasting.ipynb (Jupyter Notebook with analysis)
│
├───reports
│    └── Sales_Forecasting_Report.pdf (final report)
│
└───scripts
     └── generate_forecast.py (Python script for running analysis)
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
- Name: Jean Salgado
- GitHub: [JeanSalgadoAI](https://github.com/JeanSalgadoAI)
- Email: contact@jeansalgado.com
