# Optimal-Portfolio-Construction

## Goal: 
The goal for this project is to optimize industry portfolios through maximizing Sharpe ratio or minimizing variance. 

## Project Approach:
There are four steps that in this project:

### Step 1: Import Data from Kenneth French's Data Library
Gathered data from Kenneth French's data library, http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html.  
The Data Library contains current benchmark returns and historical benchmark returns data, which is convenient for financial modeling and data analysis. 

For this project specific, I used the 49 industry portfolios to answer a question: what is the strategy to allocate portfolios across 49 industries to generate highest Sharpe ratio or minimize variance?

### Step 2: Calculate the mean and variance of a portfolio
The return on the portfolio is the weighted sum of the individual stock returns while the portfolio variance is calculated using the standard deviation of each security in the portfolio and the correlation between securities in the portfolio.

### Step 3: Portfolio Optimization Based on Maximum Sharpe Ratio
The Sharpe ratio of a portfolio (or security) is the ratio of the expected excess return of the portfolio to the portfolio's volatility. The Sharpe optimal portfolio is the portfolio with maximum Sharpe ratio.

* Scenario 1: For Long Only
* Scenario 2: Allow Short Selling

### Step 4: Portfolio Optimization Based on Minimum-Variance
A minimum variance portfolio indicates a well-diversified portfolio that consists of individually risky assets, which are hedged when traded together, resulting in the lowest possible risk for the rate of expected return.

## Final Result:
We should first determine our strategy on investment. There is always a risk return trade off. To be more specific, higher risk is associated with greater probability of higher return and lower risk with a greater probability of smaller return.

Thus, compared maximum sharpe ratio portfolio with minimum-variance portfolio, we know that the weights allocation on each industry would have a huge difference.

Under only long scenario, a maximize sharpe ratio portfolio can be formed with: 
* Util     0.2625
* Beer     0.2082
* Drugs    0.1116
* Smoke    0.0999
* Guns     0.0931
* Rtail    0.0809
* Food     0.0748
* Softw    0.0415
* Gold     0.0275

a minimum-variance portfolio can be formed with:
* Guns     0.013140
* Drugs    0.012071
* Food     0.011728
* Agric    0.010441
* Gold     0.010131
* Hshld    0.010089
* Telcm    0.009658
* Util     0.009598
