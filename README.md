## week5_apis_project
In this project, the returns on a combined asset class, comprising of cryptocurrencies, shares and bonds is simulated for 3 different investment amounts over different periods. 

## Technologies/Libraries used
- Python
- Pandas
- Requests
- Dotenv
- Alpaca trade API
- Matplot lib
- MC Forecast tools
- Monte Carlo Simulation

## Tools used
- Git bash
- Jupyter lab
- Alpaca API
- API Alternative
- Operating system: Windows 10, 64-bit

## Asset classes
### Cryptocurrencies
- Bitcoin= 1.2 Units
- Ethereum= 5.3 Units
### Shares
- AGG Bond= 200 units
- SPY Stock= 50 units

## Statistics fetched using the API
- Bitcoin data
- Ethereum data
- Current closing prices of AGG and SPY
- 5 years historical closing prices of AGG and SPY

## Metrics calculated
- Bitcoin price
- Ethereum price
- Current value of Bitcoin units
- Current value of Ethereum units
- Total value of Crypto assets
- Price of AGG Bond
- Price of SPY Stock
- Current value of AGG Bond
- Current value of SPY stock
- Total value of Shares assets
- Combined value of all assets
- Emergency fund amount
- Assessment of financial health
- Combined asset returns for 30 years
- Summary statistics of 30 year return
- Combined asset returns for 10 years
- Summary statistics of 10 year return
- Combined asset returns for 5 years
- Summary statistics of 5 year return

## Plots created
- Pie chart comparing crypto and shares assets.
- 500 Monte Carlo simulations over 30 years
- Normal distribution of cumulative return across 500 simulations over 30 years.
- 500 Monte Carlo simulations over 10 years
- Normal distribution of cumulative return across 500 simulations over 10 years.
- 500 Monte Carlo simulations over 5 years
- Normal distribution of cumulative return across 500 simulations over 5 years.

## High-level summary
- Set the Bitcoin and Ethereum units to 1.2 and 5.3 respectively
- Fetched the data of Bitcoin and Ethereum from the Alternative API in the json format.
- Indented the Bitcoin and Ethereum data in the dictionary format.
- Retrieved the Bitcoin and Ethereum prices from the nested dictionary.
- Computed the current crypto values, corresponding to the units.
- Set the stock and bond units to 50 and 200 respectively
- Set the Alpaca API and Secret keys to fetch the data from Alpaca.
- Created the Alpaca API Object.
- Retrieved the current closing prices of SPY and AGG from Alpaca.
- Computed the value of AGG and SPY shares corresponding to the units.
- Set the monthly household income to 12000
- Created a dataframe comprising of Crypto and Shares assets and plotted a pie chart comparing them.
- Fixed the emergency fund amount as thrice the monthly income and checked if the customer's net savings exceeds the emergency fund.
- Retrieved 5 years worth of AGG and SPY shares data from Alpaca API.
- Configured 500 Monte Carlo Simulations to predict 30 years, 10 years and 5 years of returns.
- Plotted the 30-year, 10-year and 5-year simulation.
- Plotted the normal distribution of cumulative returns over 30,10,5 years.
- Fetched the summary statistics of 30,10,5 year simulations.
- Calculated the most likely lowest and highest return on 20000, 30000, 40000 and 60000.

## Conclusion
- From the Monte Carlo Simulations, it could be concluded that a 30000 investment with a 30 year waiting period would be the ideal option. The money would at least provide a return of 79845 and a maximum return potential of close to a Million Dollars.

## Contributors
- Satheesh Narasimman

## People who helped
- Khaled Karman, Bootcamp personal tutor

## References
- https://www.investopedia.com/terms/m/montecarlosimulation.asp
