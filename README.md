# quant-trading
## Data Sources
- Bitcoin Coinbase Exchange Historic Prices: https://www.coinbase.com/api/v2/assets/prices/5b71fc48-3dd3-540c-809b-f8c94d0e68b5?base=USD
- Coinbase API Docs: https://docs.pro.coinbase.com/#get-historic-rates

## Potential Features
- [ ] Last 24 hour spot price
- [ ] Last n days daily Bitcoin price data
- [ ] Google Search Trends Previous 7 days
  - "is bitcoin crashing"
  - "how to buy bitcoin"
- [ ] Last n days daily S&P price data

## Setup
1. Install Python3 and pipenv
2. `pipenv shell` to start a shell with the virtual env
3. `pipenv install` to install dependencies to the virtual env
4. `python -m ipykernel install --user --name=quant-trading` to make virtual env available as kernel for jupyter
5. `jupyter notebook`