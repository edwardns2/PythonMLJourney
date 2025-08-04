# Day 2

## Data import and set up

File: [Day 2 Workings](/files/day2.ipynb)

Day involved getting set up with `yfinance` and downloading some daily stock data. Used Apple and Tesla for ease. 

1. Installed `yfinance` through `uv`
2. Ran the API to obtain stock data for apple - had to check the docs (`https://ranaroussi.github.io/yfinance/`) on how to do this, but was simple enough in the end.
3. Converted the data to a .csv file.

## EDA

1. Imported the cvs from above into a pandas dataframe. 
2. `stock_df.info()` - snapshot of the columns and data
3. `stock_df.describe()` - snapshot of some data stats
4. `stock_df.head()` / `stock_df.head()` - First / Last rows of the data
5. `stock_df.isna().sum()` - see how many na / null values in the data set.



----------------
[Day 1](Day1.md) | [Day 3](Day3.md)