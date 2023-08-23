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
```
