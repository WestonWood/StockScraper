The WestWood 100 Stock Scraper

THIS IS NOT FINANCIAL ADVICE!!!!

This script scrapes stock info and exports it to an Excel file. There are some custom metrics I have found useful for a small compounding profit strategy. Insert your own stock tickers into the .py file to get their information.

The default time period for information/calculation is 100 days. Adjust as desired.

A "Valid Trade" day is considered any day that increases 1% or more from closing to the next day's high. Use options trading to magnify this profit if desired.
"Days Valid Trade %" indicates how frequently a valid trade day has happened in the past.

A "Green Day" is when the closing price of the current date is above the closing price of the previous date.
A "Red Day" is when the closing price of the current date is below the closing price of the previous date.

Red day to Green day is how often a stock has a red day and then the following day it is green.

Green day to Green day is how often a stock has a green day and then the following day it is green again.

"Streak Indicator" is reflective of how often a stock will 'streak,' aka hit multiple greens or reds in a row. A low value means it often flips. A high value means it likes to run red multiple days in a row or run green multiple days in a row.

RSI reflects if a stock is over or under traded. Over 70 is an overbought signal. Under 30 is an oversold signal.

Sort the last page of the Excel file "overview" to see which stocks have the best valid trade days or other metrics you care to observe.
