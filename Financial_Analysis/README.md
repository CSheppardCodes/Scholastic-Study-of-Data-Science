# Financial_Data_Analysis Readme

1. **Data Retrieval:**
   - Utilizing the yfinance library to download historical stock price data for a specified asset (e.g., AAPL, SPY) over the last 5 years.
     
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/84f4f37f-9885-487a-85a1-f227d19852bf)

2. **Candlestick Chart Visualization:**
   - Generating a candlestick chart using plotly.graph_objects to visually represent the Open, High, Low, and Close prices of the asset.
     
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/cf10a1f4-8e58-489e-a7ab-c93fe6fdc763)

3. **Advanced Charting with mplchart:**
   - Employing the mplchart library for advanced financial charting.
   - Creating a chart with candlesticks, moving averages (SMA), volume, relative strength index (RSI), and moving average convergence divergence (MACD).
     
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/094010c1-0ed1-4b49-a600-a8f5481046ac)

4. **Technical Analysis Indicators:**
   - Calculating and plotting technical indicators such as Simple Moving Averages (SMA) with different time periods (10, 50, 200) using the talib library.
     
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/59d6fe08-056f-43ff-8613-95a87fa96fd1)

5. **Simple Trading Strategy:**
   - Implementing a basic trading strategy based on the relationship between the closing price and a 50-day Simple Moving Average.
   - Generating "buy" and "sell" signals based on the strategy. Part 2 on YFinanceAnalysis

# Part 2: YFinanceAnalysis

## Buy and Hold Strategy:

1. **Data Retrieval:**
   - Utilizes the yfinance library to download historical stock price data for Microsoft (MSFT) over the last 30 years.

2. **Fixed Investment:**
   - Defines a fixed investment amount (e.g., $1000) for each investment period.

3. **Annual Investment Loop:**
   - Invests a fixed amount at the beginning of each year.
   - Computes and prints cumulative annual percent returns for each year.

4. **Monthly Investment Loop:**
   - Invests a fixed amount at the beginning of each month.
   - Computes and prints buy date, buy price, and money made for each month.
   - Displays a line plot of money over time.
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/0637c4d9-7932-457b-989e-a60773e6488e)

![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/182df426-a62c-40b8-8414-f68bf7568e1e)



## Active Trading Strategy:

5. **Data Retrieval:**
   - Uses yfinance to download historical stock price data for Microsoft (MSFT) over the last 30 years.

6. **SMA (Simple Moving Average):**
   - Calculates the Simple Moving Average (SMA) with a time period of 20.
     
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/5bac2eff-2258-4bd2-a88c-353b15834f42)

7. **Trading Logic:**
   - Implements an active trading strategy based on SMA crossovers (buy/sell signals).
   - Buys when the closing price is above the SMA.
   - Sells/keeps when the closing price is below the SMA.
   - Computes and prints buy/sell details, profit, and equity for each trade.
     
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/426bfc98-63d8-4771-a8bd-31802ba7934a)

8. **Annual Percent Return:**
   - Computes and prints the annual percent return for each year.
   - Displays a line plot of money over time.
     
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/7017e515-c21b-428a-89a2-12f7e34b842d)

## Observations:

### Buy and Hold:
- Buys and holds the asset without actively trading.
- Long-term investment perspective.

### Active Trading:
- Actively trades based on SMA crossovers.
- Short-term trading perspective.

## Conclusion:

### Observation Result:
- The presented data and analysis suggest that, in this scenario, the Buy and Hold strategy generally results in higher cumulative returns compared to active trading.
