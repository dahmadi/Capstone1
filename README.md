# FinTechProj1
### The objective of this project is to optimize one's portfolio using Monte Carlo Simulations and historical data from Alpacas spanning the past 20 years.

All parts of the Project completed by Donya Ahmadi

## Part 1 - Data (Collection, CleanUp, etc.)
### The first part included importing necessary libraries, initializing variables (including env), and importing historical data using Alpacas API. For this project, I chose AAPL, AMZN, AND MSFT, but any ticker will work. I displayed the daily return, mean, standard deviation, and last-day closing prices for my chosen tickers and the S&P 500.

## Part 2 - Monte Carlo Simulations
### A Monte Carlo simulation is a computational technique that uses random sampling to model and analyze complex systems or processes. In my code, I run 50 (can be changed) Monte Carlo simulations to optimize a portfolio's asset allocation based on historical stock data, aiming to maximize the Sharpe ratio. The results include optimal weights for each stock, the cumulative returns of the optimized portfolio, and a benchmark (S&P 500)

## Part 3 - Portfolio Optimization
### Portfolio optimization is a financial modeling technique that selects the optimal mix of assets to achieve a specific investment goal. The primary objective of portfolio optimization is to maximize returns, minimize risk, or achieve a trade-off between the two, given certain constraints. This section is an analysis of the Monte Carlo results. However, the purpose of this section is to analyze and compare the performance of the portfolio with the average weights obtained from the Monte Carlo simulations against a uniform portfolio with equal weights. 

#### Expected Return on Investment Using Optimized Weights
![Average Optimized Weights Results](https://github.com/dahmadi/FinTechProj1/blob/c1487bf12cbfb08b02fb5b3b6403d89f35714444/Project%201%20Images/Average-Optimized-Weights-Results.png)

#### Expected Return on Investment Using Uniform Weights
![Uniform_Weights_Results](https://github.com/dahmadi/FinTechProj1/blob/0a150f293328e354f01c73f0f8bb63364877ca0e/Project%201%20Images/Uniform-Weights-Results.png)

## Part 4 - Data Visualization 

#### Uniform Weights For Stocks Data
![Uniform-Weights-Data](https://github.com/dahmadi/FinTechProj1/blob/86093b1e5a41690c97f7b60323832578541b6b3e/Project%201%20Images/Uniform-Weights-Data.png)

#### Average Optimized Weights For Stocks Data
![Average-Opt-Weight-Data](https://github.com/dahmadi/FinTechProj1/blob/86093b1e5a41690c97f7b60323832578541b6b3e/Project%201%20Images/Opt-Weights-Data.png)

#### Expected Return On Investment (Optimized) Graph
![Return-Investment](https://github.com/dahmadi/FinTechProj1/blob/86093b1e5a41690c97f7b60323832578541b6b3e/Project%201%20Images/Expected-Return-investment.png)

#### 90% Confidence Interval Graph

![confidence-interval](https://github.com/dahmadi/FinTechProj1/blob/86093b1e5a41690c97f7b60323832578541b6b3e/Project%201%20Images/90-confidence-interval.png)

The 90% confidence interval for the values in the recentReturns dataset is approximately [14.91, 692.18]. This means that there is a 90% confidence that the true values lie within this range
