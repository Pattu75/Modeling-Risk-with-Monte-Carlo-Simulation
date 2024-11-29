In this project, we have used Monte carlo Simulation to build a model that help us predict the stock price of MSFT and also use VaR to assess the risk of buying and holding MSFT.

Part 1: Stock Price Prediction Model
- We imported over 20 years Microsoft prices data from Yahoo finance and calculated the daily log returns. 
- Using the historical log returns, we have calculated the mean, standard deviation and variance. 
- Then we calculated the drift, which is the mean of the returns with consideration of the variance. 
- Based on the probability distribution and the key statistic measures of historical returns. 
- We generated a random normal distribution to simulate the daily returns of the following year in 10,000 scenarios. 
- Based on the 10,000 results we examined the best, worst and average stock price scenarios. 
- We also looked at the range of the stock prices within a 68% probability and 95% probability. 

Part 2: Value at Risk Assessment Model
- In this case, we will use monte Carlo simulation to assess the risk of purchasing 1,000 shares of MSFT shares and holding them for one month. 
- We will look at a 30-day historical data of Microsoft in this model. 
- Instead of analyzing the data directly, we'll pull key information from different sources. 
- The parameters we'll need in this model include the value of the investment at the current time and the volatility of the stock. 
- Then we use these parameters to simulate the investment return of holding the stock for one month period. We'll generate 5,000 scenarios. 
- Finally, based on how the 5,000 returns are distributed, we'll find out the one-month VaR at 90%, 95% and 99% confidence from these simulation results.
