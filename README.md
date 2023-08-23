# TIME SERIES ANALYSIS ON STOCK PRICE
## WHAT IS TIME SERIES ANALYSIS?
A time-series dataset is a sequence of data collected over an interval of time. Time series analysis means analyzing and finding patterns in a time series dataset. The time interval of a time series data can be weekly, monthly, daily, or even hourly time intervals.

## EXAMPLES FOR TIME SERIES ANALYSIS:
Stock price data, monthly sales data, daily rainfall data, hourly website traffic data are some examples of time-series data that you will get to solve business problems.

## HOW THE DATA BEEN COLLECTED ?
1. I HAVE INSTALLED YFINANCE TO GET STOCK PRICE DATA OF APPLE
   (YFINANCE IS NOTHING BUT YAHOO FINANCE WHERE WE GET CURRENT STOCK PRICE DATA USING BELOW CODE)
3. IMPORTED NECESSARY LIBRARIES LIKE PANDAS, TIMEDELTA,DATE TIME
4. ``` PYTHON
   CODE FOR GETTING DATA FROM YFINANCE
   d1 = today.strftime("%Y-%m-%d")
   end_date = d1
   d2 = date.today() - timedelta(days=360)
   d2 = d2.strftime("%Y-%m-%d")
   start_date = d2

   data = yf.download('AAPL', 
                      start=start_date, 
                      end=end_date, 
                      progress=False)
   print(data.head())

## PROCESS OF TSA?
1. DATA CLEANED
2. COLUMNS ARRANGED BY CHANGING THE COLUMNS NAME
3. ANALYSED THE INCREASING AND DECREASING STOCK PRICE USING PLOTLY GRAPH(LINE CHART, BAR GRAPH, CANDLE STICK CHART)
## USING LINE PLOT
![newplot](https://github.com/keerthy-analyst/TIME-SERIES-ANALYSIS-ON-STOCK-PRICE-/assets/115634164/128912bd-01c5-4162-b4e3-171230ba6fec)
## USING CANDLE STICK PLOT
![newplot (1)](https://github.com/keerthy-analyst/TIME-SERIES-ANALYSIS-ON-STOCK-PRICE-/assets/115634164/f4959aea-0a1c-46bf-be07-bc4d4c279606)

## CONCLUSION:
I hope you now have a better understanding of how to perform time series analysis using Python and all the available time series analysis visualizations. A collection of data over a period of time is referred to as a time-series dataset. Time series analysis is the process of looking for patterns in a time series collection. Time series data might include intervals that are weekly, monthly, daily, or even hourly. I hope you enjoyed reading this essay on Python-based time series analysis.




