# Financial Planner


## Personal Finance Planner

## Collect Crypto Prices Using the requests Library

Use the requests library to fetch the current price in US dollars of bitcoin (BTC) and ethereum (ETH) using the Alternative Free Crypto API endpoints 

Parse the API JSON response to select only the crypto prices and store each price in a variable.
Hint: Be aware of the particular identifier for each cryptocurrency in the API JSON response - the bitcoin identifier is 1 whereas ethereum is 1027.

Compute the portfolio value of cryptocurrencies and print the results.



## Collect Investments Data Using Alpaca: SPY (stocks) and AGG (bonds)

Set the Alpaca API key and secret key variables, then create the Alpaca API object using the tradeapi.REST function from the Alpaca SDK.

Format the current date as ISO format

Get the current closing prices for SPY and AGG using Alpaca's get_barset() function. Transform the function's response to a Pandas DataFrame and preview the data.

Pick the SPY and AGG close prices from the Alpaca's get_barset() DataFrame response and store them as Python variables. Print the closing values for validation.

Compute the value in dollars of the current amount of shares and print the results.



## Savings Health Analysis

To analyze savings health, create a DataFrame called df_savings with two rows. Store the total value in dollars of the crypto assets in the first row and the total value of the shares in the second row.

Use the df_savings DataFrame to plot a pie chart to visualize the composition of personal savings.

Use if conditional statements to validate if the current savings are enough for an emergency fund. An ideal emergency fund should be equal to three times your monthly income.

If total savings are greater than the emergency fund, display a message congratulating the person for having enough money in this fund.

If total savings are equal to the emergency fund, display a message congratulating the person on reaching this financial goal.

If total savings are less than the emergency fund, display a message showing how many dollars away the person is from reaching the goal.



# Retirement Planning

Use the Alpaca API to fetch five years historical closing prices for a traditional 40/60 portfolio using the SPY and AGG tickers to represent the 60% stocks (SPY) and 40% bonds (AGG) composition of the portfolio. Make sure to convert the API output to a DataFrame and preview the output.

Configure and execute a Monte Carlo Simulation of 500 runs and 30 years for the 40/60 portfolio.

Plot the simulation results and the probability distribution/confidence intervals.



## Retirement Analysis

Fetch the summary statistics from the Monte Carlo simulation results.

Given an initial investment of $20,000, calculate the expected portfolio return in dollars at the 95% lower and upper confidence intervals.

Calculate the expected portfolio return at the 95% lower and upper confidence intervals based on a 50% increase in the initial investment.




