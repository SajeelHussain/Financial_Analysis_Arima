# Financial Analysis with ARIMA and Time Series

This repository contains a collection of Jupyter notebooks for time series analysis and ARIMA modeling, with a focus on financial data. The notebooks guide users through key steps in time series analysis, including stationarity testing, autocorrelation analysis, and ARIMA model implementation.

## Contents

- **ACF_PACF_Stock_Returns.ipynb**: Analyzes the autocorrelation (ACF) and partial autocorrelation (PACF) of stock returns, including data import and visualization.
- **PACF_and_ACF.ipynb**: Similar to the above, focusing on ACF and PACF analysis for time series data.
- **Stationarity.ipynb**: Demonstrates methods for testing the stationarity of time series data using statistical tests and visualizations.
- **ARIMA.ipynb**: Implements ARIMA modeling for time series forecasting, including model fitting and diagnostics.
- **ARIMA_2.ipynb**: Further ARIMA modeling with additional examples and visualizations.
- **ARIMA_3.ipynb**: Continues ARIMA modeling and analysis on different datasets or scenarios.
- **ARIMA_Champagne.ipynb**: Applies ARIMA modeling to the classic Champagne sales dataset, with thorough analysis and visualization.

## Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab
- Recommended packages (install with pip if missing):
  - pandas
  - numpy
  - matplotlib
  - statsmodels
  - seaborn

### Installation
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd Financial_Analysis_Arima-main
   ```
3. (Optional) Create and activate a virtual environment.
4. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
   Or manually install:
   ```bash
   pip install pandas numpy matplotlib statsmodels seaborn
   ```

### Usage
Open any notebook in Jupyter and follow the instructions in the cells. Each notebook is self-contained and demonstrates a specific aspect of time series analysis or ARIMA modeling.

## Project Structure
- Each notebook is focused on a particular analysis or dataset.
- Visualizations and statistical tests are included to guide interpretation.
