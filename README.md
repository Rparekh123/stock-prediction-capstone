# Stock Price Prediction

## Business Understanding 

The stock market is a great way to grow and invest your money. As time went by retail investors have been gaining access to proper tools utilized by institutions in order to help with their investments. With many different factors affecting a stock price it is tough to choose when to buy or sell a stock. This project utilizes machine learning to help gauge investors when to buy or sell a specific stock. The main stocks that will be counted for are the top 10 highest weighted stocks in the QQQ ETF. The QQQ tracks the Nasdaq-100 which is also an index.

## Breakdown of the top 10 Stocks
![newplot](https://user-images.githubusercontent.com/52425750/139149498-37716f58-0e51-4a01-ab89-392a9a4bde20.png)
In the plot above we see the breakdown of specific sectors in QQQ. 50% of the stocks are in the sector of information technology. Due to this high weightage of the tech sector we will be focusing on the stocks within this sector.
![newplot (1)](https://user-images.githubusercontent.com/52425750/139149738-dea86252-a0a9-40e4-9f1a-d5ee1ab7819e.png)
In this pie chart it breaks down the top 10 highest weighted stocks within the QQQ. All 10 of these companies are highly regarded in the technology industry. That is why these stocks were chosen for the models.

## Data sources
Historical data was collected from  the Yahoo finance library. The data starts from the year of 2009 and goes up till the current date. The yahoo finance library is very simple and easy to use. The data collected were the daily prices of the stocks, the high, low, open, close, dividend and stock split. For the modeling the close prices were used. This is an example of one of the stocks price chart.
![newplot (2)](https://user-images.githubusercontent.com/52425750/139150397-ba3412ce-4523-4234-af7b-ab651293f42a.png)

## Modeling and Forecasting
For the models that were compared, there were 3 main models. The ARIMA, Prophet, and a SARIMAX model.
Each provided a forecast on a testing set to compare which model would provide the lowest error score. The lowest error score meant higher confidence in the models prediction for the next day.
