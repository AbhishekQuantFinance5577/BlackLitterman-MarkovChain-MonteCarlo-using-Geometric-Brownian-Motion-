# Black-Litterman-MarkovChain-MonteCarlo-using-Geometric-Brownian-Motion-
This project involves optimizing portfolios and simulating prices for stocks, cryptos using Python. I calculated optimal portfolio weights to minimize variance and maximize returns, used the Black-Litterman model, and plotted results. I also used MCMC to simulate DJIA and crypto returns, analyzing the best samples.
Detailed Description - 

Project Description: Portfolio Optimization and Price Simulations
Part A: Portfolio Optimization
Problem A1: Stock Portfolio Optimization

Data Collection: Downloaded data for five selected stocks from Yahoo Finance, ensuring a minimum of 252 observations.
Optimization:
Minimize Portfolio Variance: Calculated the optimal weights to minimize portfolio variance using standard mean-variance optimization.
Black-Litterman Optimization: Applied the Black-Litterman model to find the optimal portfolio weights.
Visualization: Plotted the optimal portfolio weights from both optimization methods on the same graph.
Analysis: Compared and contrasted the differences in optimal weights from the two methods using investment reasoning.
Problem A2: Crypto Portfolio Optimization

Data Collection: Downloaded data for five selected cryptocurrencies from CoinMarketCap, ensuring a minimum of 252 observations.
Optimization:
Maximize Portfolio Return: Calculated the optimal weights to maximize portfolio returns using standard mean-variance optimization.
Black-Litterman Optimization: Applied the Black-Litterman model to find the optimal portfolio weights.
Visualization: Plotted the optimal portfolio weights from both optimization methods on the same graph.
Analysis: Compared and contrasted the differences in optimal weights from the two methods using investment reasoning.
Problem A3: Descriptive Statistics

Descriptive Statistics: Derived the descriptive statistics for the optimal portfolios obtained in Problem A1.
Analysis: Commented on the differences in statistical indicators between these optimal portfolios.
Distribution Analysis: Analyzed and commented on the distribution of the optimal portfolio returns obtained in Problem A1.
Part B: Stock and Crypto Price Simulations (MCMC)
Problem B1: Stock Price Simulation

Data Collection: Downloaded DJIA data from CoinMarketCap, ensuring a minimum of 252 observations.
Simulation: Used Markov Chain Monte Carlo (MCMC) to simulate stock market returns (both simple and log returns) using the Geometric Brownian Motion (GBM) model.
Analysis: Evaluated and commented on the best sample among the simulations using investment logic.
Problem B2: Crypto Price Simulation

Data Collection: Downloaded data for a selected cryptocurrency from CoinMarketCap, ensuring a minimum of 252 observations.
Simulation: Used MCMC to simulate cryptocurrency returns (both simple and log returns) using the GBM model.
Analysis: Evaluated and commented on the best sample among the simulations using investment logic.
This project focuses on practical applications of portfolio optimization and advanced price simulation techniques, providing insights into optimal asset allocation and potential future price movements for both stocks and cryptocurrencies.
