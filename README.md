# quant-strategy-backtest
Backtesting moving average, RSI, and combined trading strategies in Python

## Objective
The objective of this project is to test and analyze different rule-based Quant Trading Strategies and their performance relative to a Buy and Hold approach.

## Quant Trading Strategies Tested
Moving Average Strategy - 20 days vs 50 days  
RSI Trading Strategy  
Combined Trading Strategy - Moving Average and RSI Filtering

## Key Features
Data Retrieval of Stock Prices using `yfinance`  
Calculate Returns  
Moving Average Indicators  
RSI Indicator  
Strategy Signal Generation  
Cumulative Returns  
Sharpe Ratio Calculation  
Drawdown Analysis  
Transaction Costs  
Stop Loss  
Parameter Tuning  
Multi-Asset Testing

## Tools and Technologies Used
Python  
pandas  
matplotlib  
yfinance

## Key Results
### AAPL - Apple Inc Stock (2023)
Buy and Hold Final Value  
Moving Average Trading Strategy Final Value  
RSI Trading Strategy Final Value  
Combined Trading Strategy Final Value  

### Multi-Asset Test  
AAPL - Apple Inc  
TSLA - Tesla Inc  
NVDA - NVDA Inc

## Insights
- Buy and hold outperformed all strategies for AAPL in 2023.
- The moving average strategy partially captured the trend but trailed behind the buy and hold strategy.
- The RSI strategy underperformed because it spent too much time out of the market in a strong uptrend.
- The combined strategy was too conservative and resulted in minimal market exposure.
- The performance of the strategy varied across assets, indicating that it does not perform equally well across all stocks.

## Why This Project Matters
The project is important because it shows how to apply quantitative finance concepts. These concepts include:
- Financial data analysis
- Development of technical indicators
- Backtesting of trading strategies
- Evaluation of performance
- Evaluation of risk

## Future Improvements
Future improvements include:
- Testing other technical indicators such as MACD or Bollinger Bands
- Incorporating slippage costs
- Optimizing technical indicators across multiple assets
- Creating a portfolio-level backtest rather than individual stock-level backtests
