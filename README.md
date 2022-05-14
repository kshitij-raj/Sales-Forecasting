# Sales Forecasting

## Problem Statement
Rossmann is a European drug distributor which operates over 3,000 drug stores across seven European countries. Since a lot of drugs come with a short shelf life, that is, they do not have a long expiry date, it becomes imperative for Rossmann to accurately forecast sales at their individual stores. Currently, the forecasting is taken care of by the store managers who are tasked with forecasting daily sales for the next six weeks. 

As expected, store sales are influenced by many factors, including promotional campaigns, competition, state holidays, seasonality, and locality.

With thousands of individual managers predicting sales based on their unique circumstances and intuitions, the accuracy of the forecasts is quite varied. To overcome this problem, the company has decided to build a forecasting model to forecast the daily sales for the next six weeks.

Note - Since the company is just embarking on this project, the scope has been kept to nine key stores across Europe. The stores are key for the company keeping in mind the revenue and historical prestige associated with them. These stores are numbered - 1,3,8,9,13,25,29,31 and 46.

## Model Building Approach
* Data Loading

* Exploratory data analysis (EDA)
    * Merge the datasets.
    * Filter nine key stores data.
    * Create Derived Metrics
    * Perform basic sanity checks.
    * Remove outliers.
    * Visualise the sales data for every store.

* Create User Define Function(UDF) and perform preprocessing of data before model building.

* Model Building for all 9 stores
    * Visualise Trend, Seasonality, and Residuals for stores.
    * Perform Adfuller Test to check the stationarity of the sales data.
    * Perform data Difference if time series data is not stationary.
    * Perform Johansen Test to check cointegration between two variales.
    * Split the data into Train and Test.
    * Build ARIMA Model.
    * Build SARIMA MODEL.
    * Build SARIMAX Model.
    * Build VARMAX Model.
    * Perform Model Evaluation to chek which is the best model from the above is predicting the sales more accurately.

