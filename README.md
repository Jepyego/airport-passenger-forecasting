#  Airport Passenger Forecasting Using ARIMA in R

##  Project Overview

This project analyzes historical airport passenger traffic data and forecasts future passenger volumes using the ARIMA (AutoRegressive Integrated Moving Average) time series forecasting model in R.

The project demonstrates the complete data analysis workflow, including data preparation, exploratory analysis, stationarity testing, model development, forecasting, and model evaluation.

---

##  Objectives

- Import and clean airport passenger data
- Perform exploratory data analysis
- Convert the data into a monthly time series
- Test for stationarity using the Augmented Dickey-Fuller (ADF) test
- Build an optimal ARIMA forecasting model
- Forecast passenger traffic for the next 12 months
- Evaluate model performance using residual diagnostics

---

##  Technologies Used

- R
- RStudio
- R Markdown
- readxl
- dplyr
- forecast
- tseries
- ggplot2

---

##  Project Structure

```
Airport-Passenger-Forecasting/
│
├── Data/
│   └── RAW DATA BY AIRPORT.xlsx
│
├── Output/
│   ├── forecast_plot.png
│   └── time_series_plot.png
│
├── Airport-Analysis-Review.Rmd
├── Airport-Analysis-Review.pdf
├── README.md
└── .gitignore
```

---

## Analysis Workflow

1. Data Import
2. Data Cleaning
3. Time Series Creation
4. Data Visualization
5. Stationarity Testing (ADF Test)
6. ARIMA Model Selection
7. Passenger Forecasting
8. Model Evaluation

---

##  Results

- Successfully imported and prepared airport passenger data.
- Conducted stationarity testing using the Augmented Dickey-Fuller test.
- Built an ARIMA forecasting model using the `forecast` package.
- Generated a 12-month passenger traffic forecast.
- Evaluated the model using residual diagnostics.

---

##  Sample Visualizations

- Monthly Passenger Traffic Time Series
- 12-Month Passenger Forecast

---

##  Skills Demonstrated

- Data Cleaning
- Time Series Analysis
- Forecasting
- Statistical Testing
- Data Visualization
- R Programming
- R Markdown
- Reproducible Research

---

##  Future Improvements

- Compare ARIMA with Prophet and LSTM models.
- Develop an interactive dashboard using Shiny.
- Incorporate additional predictors such as seasonal events and economic indicators.



##  Author

**Abigael Sugut**

Bachelor of Science in Data Science and Analytics

The Co-operative University of Kenya


