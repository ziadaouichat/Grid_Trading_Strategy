# Grid_Trading_Strategy
This is a Grid Trading Strategy build in Python
we test the grid trading strategy, a simple approach that doesn't require any technical indicators. 
We use python to test and trade, the backtest shows a steady equity increase over 2 months of data using the 5-minute timeframe. 
It scores almost 5.7 for the Sharpe Ratio. 
The idea is to create a grid of values on top of our chart and open long and short positions at the same time. 
There are different ways to deal with losing trades. It works best on lower timeframes and is a good candidate for algorithmic trading. 
One adjustable factor depends on the timeframe and asset volatility.
