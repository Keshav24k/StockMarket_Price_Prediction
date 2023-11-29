# StockMarket_Price_Prediction

## Problem Setting:

The stock market is traditionally a difficult area to navigate for inexperienced traders with limited knowledge of basic chart patterns and indicators. The high barrier of entry causes the stock market to be a risky environment driving investors towards financial advisors, thereby reducing their potential profits. An algorithmic stock predictor is highly valuable to investors if it is able to predict future price movements, as the general predicted trend can be utilized to target points of entry and exit for specific commodities. Additionally, having reliable information in hand reduces the emotional influence that is often detrimental to trading returns. Algorithmic stock market predictors are notoriously difficult to implement, but several large institutions use them successfully to drive their trading.
## Problem Definition:

The problem being addressed simulates a generic retail investor’s portfolio containing five commonly available commodities. The investor is new to trading and is interested in improving their strategic entry and exit points for the commodities in their portfolio. The portfolio contains a range of investments, from low-risk/long-term to high-risk/short-term. A machine learning algorithm will be developed to visualize and analyze the price history of the portfolio commodities to predict future prices and volatility. The prediction model will then be assessed for accuracy to better inform future trading reliance on the model.
Data Source:
All data will be sourced from Yahoo Finance and will include the previous five years of daily price history. The datasets utilized will include daily open, close, high, low, and volume. Data will be selected for five commodities, specifically MSFT, TSLA, DIS, VGSTX, and BTC.

## Data Description:

The dataset has 5 years of data observations with 7 attributes - 1 date and 6 numerical variables. It provides the historical price values and the volume traded for the stocks. The Close is a price
attribute that will serve as the target variable as it helps us predict the future price of the stock and the volume will be used as the predictor. A test dataset will be set aside to evaluate the machine-learning models. Features such as “Open”, “High”, and “Low” etc. will be used to assess the stocks and develop the machine learning model.
