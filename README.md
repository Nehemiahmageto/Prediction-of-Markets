# Stock-Market-Prediction

**Stock-Prediction-Models**, Gathers machine learning and deep learning models for Stock forecasting, included trading bots and simulations.

Understanding the volatility of the stock market is key for an investor to understand where their stock falls

## APPLE STOCK

I worked on apple stock data collected from Yahoo Finance.
**Yfinance** python library is the recomended library to be used to scrap yahoo stock data from the web.

Models used are:
- GARCH/ARCH
- ARIMA

### GARCH
THe Arch python library was use here.

In order to ensure the highest accracy we have to come with the best p d q for the GARCH model. To ensure this we information theory based mathematical models for model selection.

The two mian candidates are;
- AIC (Akaike information criterion)
+ BIC(Bayesian information criterion)

#### Bayesian information criterion
BIC perfoms betters in larger data sets compared to AIC which is more preffered for smaller datasets. In this model BIC is the best for feature selection .

I used GARCH model to test train my model and check for the volatility of the stock market values. 

##### Results
- We had an RMSE score of 2 which shows that prediction model can be depended on.
+ We can see that at the end our volatility prediction range around 2% which is encouraging for investors and positive news.
