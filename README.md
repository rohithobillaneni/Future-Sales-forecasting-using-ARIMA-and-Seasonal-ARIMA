# Future-Sales-forecasting-using-ARIMA-and-Seasonal-ARIMA

This notebook contains Python code for implementing Autoregressive Integrated Moving Averages (ARIMA) and Seasonal ARIMA models for time series forecasting.

## Getting Started

To get started, follow the steps outlined below:

### Step 1: Install Dependencies

Ensure you have the necessary dependencies installed. You can install them using pip:

```bash
pip install numpy pandas matplotlib statsmodels
```

### Step 2: Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/rohithobillaneni/Future-Sales-forecasting-using-ARIMA-and-Seasonal-ARIMA
```

### Step 3: Run the Notebook

Open the `ARIMA and Seasonal ARIMA.ipynb` notebook in Jupyter Notebook or JupyterLab.

## Usage

The notebook contains the implementation of ARIMA and Seasonal ARIMA models. You can modify the code and dataset paths as needed for your own data.

## Dataset

The dataset used in this example is "perrin-freres-monthly-champagne.csv", which contains monthly champagne sales data from 1964 to 1972.

## Cleaning the Data

The notebook performs data cleaning tasks such as renaming columns, handling missing values, and converting dates to datetime format.

## Testing for Stationarity

The stationarity of the time series data is tested using the Augmented Dickey-Fuller (ADF) test. If the p-value is less than 0.05, the data is considered stationary.

## Differencing

If the data is not stationary, differencing is applied to make it stationary.

## Auto Regressive Model (AR) and Moving Average Model (MA)

The notebook uses the Auto Correlation Function (ACF) and Partial Auto Correlation Function (PACF) plots to determine the parameters (p, d, q) for the ARIMA model.

## Model Fitting and Prediction

Finally, the ARIMA or Seasonal ARIMA model is fitted to the data, and predictions are made for future time periods.
