## Dataset link: https://finance.yahoo.com/quote/TTM/history?p=TTM
<i> This dataset contains all the previous record of stock price of Tata Motors Company. </i> <br>
Note: The Dataset link is not working in a browser for some time due to some technical bug but in a model, it is working fine and the dataset is fetchable.
## To use the dataset in the code you can use this command
<code> 
import yfinance as yf
import datetime as dt
df = yf.download('TTM', dt.datetime(2012,1,1) , dt.datetime(2023,1,7)) </code>
