# stock-price-prediction
In this notebook, we aim to analyse and model a time series in the form of stock price analysis and forecast: 
   - create an equally weighted index with the top 10 performing stocks from the S&P500 benchmark,
   - preprocess and handle missing data,
   - perform exploratory data analysis (EDA),
   - decompose the time series in order to analyse the underlying patterns and identify trends and seasonality,
   - stationarize the data by implementing different methods and choosing the best performing model based on statistical metrics,
   - implement statistical models, both classical and more advanced, for time-series forecast,
   - perform model comparison and choose best model based on statistical metrics.
     
# stock-price-prediction-ml
In this notebook, we implement machine learning algorithms in order to forecast stock prices using an equally weighted index. 
  - we start by creating an equally weighted index (EWI) with data pulled from the yfinance API
  - pull macroeconomic and setiment features, using FRED and Vader repectively, as alternate data for 
     feature engineering
  - this is then followed by EDA of the EWI
  - data normalization is carried out in order to scale data for application of ML models
  - use a baseline model for forecast
  - use data to train ML models for forecast
  - model evaluation is then carried out
  - hyperparameter optimization for optimal model performance
  - backtesting
