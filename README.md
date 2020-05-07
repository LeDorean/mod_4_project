# mod_4_project
This is the mod4 project repo for Luc Batty, Isabel Susan Joseph, and Vittorio Scacchetti.
The aim of the project is to identify the top five zipcodes in the USA real estate investment market. 
To this end, the team conducted a time series analysis on the housing prices of US zipcodes.

Repo contents:
---
Data sets:
- zillow_data.csv: US home values data (project starter data), obtained from https://www.zillow.com/research/data/
- fmr_data.csv: data about fair-market-rent rates over time, prepared by the team (source data obtained from https://www.huduser.gov/portal/datasets/fmr.html)
- top_10_zipcodes.csv: combined dataframe for top ten zipcodes, prepared by the team

Jupyter notebooks:
- market_analysis.ipynb: ARIMA time series modeling for the US housing market as a whole
- top_ten_zipcodes_historical.ipynb: EDA and data extraction identifying the top ten historical performers
- arima_models.ipynb: ARIMA time series models for each of the top ten historic zipcodes
