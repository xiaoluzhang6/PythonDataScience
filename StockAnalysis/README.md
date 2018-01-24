
# Stock Analysis<br><br>

This is a Time Series practice with Pandas. We are looking at a set of stock price data for Apple from the date '1982-01-01' (although first available date was the 4th) and '2018-01-23'. Below is the plotted graph of the closing price:<br>

<img width="773" alt="screen shot 2018-01-23 at 2 18 13 am" src="https://user-images.githubusercontent.com/32026039/35270474-178de0b6-ffe4-11e7-9c65-487e94f6a808.png">

<br><br>
The method used here is pct_change, which calculates the percent change with a set period; here it is set to 5, which is 5 days window. nlargest is used to get the five largest stock price surge.<br>

Highest surge happened within three days of eachother, for example, in 1997, highest surge time frames were consecutively starting August 1st, 2nd, and 3rd; in 1998, highest surge was between January 1st and 6th, as well as January 3rd and 8th. These are not sudden surgest that happen over one day, but has a pattern that starts to rise on day one and continues to reach its peak, then finally starts to go downward.<br>
I also plotted a graph for highest closing price surge over rolling quarters (financial year ending in September)<br><br>

<img width="778" alt="screen shot 2018-01-23 at 4 58 31 pm" src="https://user-images.githubusercontent.com/32026039/35308895-b17ad93e-005e-11e8-82b9-ecc63ce4221a.png"><br><br>

## Discussion<br>

Apple was newly found in 1980, trading at two dollars per share, and the market was very optimistic. Right up until 1983 before Steve Jobs left, stock price has be risen to a peak of eight dollars per share. There is a sharp dive in 1985 when Jobs left the company. In 2004, there is a sharp bump in stock price when the new and revamped iPod mini hit the market; many investors jumped onto the bandwagon. See source list for full article (Fortune.com)<br><br>

## Sources<br>
General syntax help from MSIS2802 TA<br><br>

Datareader function:<br>
https://stackoverflow.com/questions/22991567/pandas-yahoo-finance-datareader<br>
http://pandas-datareader.readthedocs.io/en/latest/remote_data.html#yahoo-finance<br><br>

Plotting graphs:<br>
https://ntguardian.wordpress.com/2016/09/19/introduction-stock-market-data-python-1/ <br>
https://stackoverflow.com/questions/12444716/how-do-i-set-the-figure-title-and-axes-labels-font-size-in-matplotlib <br><br>

Pandas Documentation:<br>
https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.nlargest.html<br> 
https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.pct_change.html <br>
https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.shift.html <br><br>

Calculate rolling average:<br>
https://stackoverflow.com/questions/46098931/pandas-calculate-change-across-rolling-timeframe <br><br>

Pandas Resampling:<br>
https://www.youtube.com/watch?v=r0s4slGHwzE<br>
https://stackoverflow.com/questions/17001389/pandas-resample-documentation <br><br>

Apple Company Info:<br>
http://fortune.com/2012/10/05/apple-from-1980-to-2012/<br> 
