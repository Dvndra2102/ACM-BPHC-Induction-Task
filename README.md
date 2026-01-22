# ACM-BPHC-Induction-Task
The task was divided into:
1) Probability Section, and
2) Coding Section.

**Questions in Probability Section:**

1) Let’s say you have 10 coins where the probability of getting heads for ith coin is 1/(i+1). All are tossed at once and the probability of getting odd number of heads is p, then: 
a. p < 1/3 
b. 1/3 < p < ½ 
c. p = ½ 
d. ½ < p < 1

2) Ellen bought a share of stock for $10, and it is believed that the stock price moves (day by day) as a simple random walk with p = 0.55. What is the probability that Ellen’s stock reaches the high value of $15 before the low value of $5? 
a. 0.35   b. 0.73   c. 0.50   d. 0.29

3) Suppose only 80% of all drivers in a certain city regularly wear a seat belt. A random sample of 500 drivers is selected. What is the probability that more than 400 of them wear a seat belt? 
a. 0.5   b. 0.52   c. 0.48   d. None of these

4) Five Light Bulbs Problem:
You have five light bulbs, all of which are off. In each turn, you randomly select one of the five bulbs and flip its state (if it's on, you turn it off; if it's off, you turn it on). The objective is to find the expected number of turns until all five light bulbs are off again.

5) All Odds Before Even:
What is the probability of rolling a fair six-sided die and having all three odd numbers (1, 3, 5) appear at least once before the first even number (2, 4, 6) is rolled?

**Coding Section:**

1) Sharpe Ratio & Risk Analysis: 
Evaluate the performance of a stock with respect to risk.
Tasks:
Select any 10 stocks from the NIFTY50 and download the last 1 year of daily data.
For each stock, calculate:
Daily returns
Average daily return
Standard deviation of daily returns
Annualized Sharpe ratio (assume risk-free rate = 0)
Plot a histogram of daily returns with mean and standard deviation marked. (for any 1 stock)
Plot a bar chart of Sharpe ratios for these stocks to compare risk-adjusted performance.
Print which stock performed the best on a risk-adjusted basis.

2) Volume Trading Strategy: 
Implement a basic trading strategy using volume of trades 
Tasks: 
Choose any stock from the given list below and download 6 months of daily OHLCV data (Open, High, Low, Close, Volume) using yfinance or nsepy modules. 
Compute the 20-day average trading volume. 
If the Volume of a particular day hits more than 2.0 times its previous 20-day average volume, mark it as a buy signal in the bar chart of the stock. 
If the Volume of a particular day goes less than 0.5 times its previous 20-day average volume, mark it as a sell signal in the bar chart. 
Push the Buy and Sell dates to a csv file. 
Make sure it is neat and informative. 
List of Stocks: 
a) Balrampur Chini Mills 
b) Afcons Infrastructure Ltd 
c) Sundaram Finance 
d) Jindal Stainless Steel Ltd 
e) Muthoot Finance
f) Bharat Heavy Electricals Ltd 
These are Midcap/Smallcap Stocks which undergo more fluctuations than the NIFTY50 stocks.

