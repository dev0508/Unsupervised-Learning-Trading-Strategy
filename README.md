# Unsupervised-Learning-Trading-Strategy

I am analyzing 8 years of data for all S&P 500 stocks, calculating various momentum metrics and betas for each stock and its respective date. I cluster stocks based on the Relative Strength Index (RSI), selecting the ones with higher momentum. I then apply an unsupervised machine learning model to the selected stocks to optimize portfolio allocation and maximize return for the portfolio for last 8 years. The model calculates an annualized mean (expected) return of each stock and a sample covariance matrix. Using these parameters, I used an Efficient Fourier Setup to optimize my portfolio to obtain the highest return for a given level of risk and I further improve the returns by maximizing the Sharpe Ratio. The model returned approximately 100% over S&P 500 in 8 years.  

![image](https://github.com/user-attachments/assets/63669fe6-3ce4-49f0-8622-2e8fa8561f47)
