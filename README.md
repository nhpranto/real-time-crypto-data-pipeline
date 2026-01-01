# Real-Time Cryptocurrency Data Automation (Python)
Overview

This project uses the CoinMarketCap API to collect real-time cryptocurrency market data and analyze price changes over time. The script automatically pulls live data, processes it using Pandas, and stores historical records for analysis.

Each time the program runs, it retrieves current market prices, making this a real-time dataset.

# Key Features

Connects to a live cryptocurrency API

Fetches top 50 cryptocurrencies in USD

Converts JSON API responses into structured tables

Automatically adds timestamps to each data pull

Stores historical market data

Analyzes percentage price changes over multiple timeframes

Performs data aggregation and transformation using Pandas

# Technologies Used

Python

CoinMarketCap API

Pandas

Requests

JSON

Real-Time Data Source

Data is pulled directly from CoinMarketCap’s live API

Prices update on every execution

No static or preloaded dataset is used

Suitable for real-time tracking and automation

# Data Processing & Analysis

Normalizes nested JSON API responses

Creates structured Pandas DataFrames

Groups data by cryptocurrency name

Calculates average percentage changes for:

1 hour

24 hours

7 days

30 days

60 days

90 days

Reshapes data for analysis and visualization readiness

Project Structure

API request handling

Data extraction and cleaning

Automated data collection function

Historical data storage

Exploratory market analysis

# Use Cases

Cryptocurrency market analysis

Real-time financial data collection

API automation examples

Data analytics portfolio project

# Future Improvements

Add data visualizations

Store data in a database

Schedule automatic API runs

Create a dashboard for live tracking
