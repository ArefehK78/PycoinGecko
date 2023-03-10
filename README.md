# PycoinGecko
Creating Bitcoin Candlestick Chart Over Past 30 Days

I used the API to get the price data for 30 days with 24 observation per day, 1 per hour. 
Finding the max, min, open, and close price per day meaning we will have 30 candlesticks and use that to generate the candlestick graph. 
Although I used the CoinGecko API I also used a Python client/wrapper for the API called PyCoinGecko. 
PyCoinGecko will make performing the requests easy and it will deal with the enpoint targeting.
