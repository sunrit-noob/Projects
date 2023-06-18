print("Checking ....")
import pandas as pd
import yfinance as yf

stock = yf.Ticker('^NSEI)
try:
  df = stock.history(period = "5y")
  the_file = 'github.com/sunrit-noob/Projects/NSEI.csv'
  df.to_csv(the_file)
except Exception as ex:
  print(ex)
