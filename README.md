# Financial_analysis Tool
This Python project is designed to fetch and analyze stock data using APIs from TwelveData and Financial Modeling Prep (FMP). It collects company profile information, stock price data, earnings estimates, growth estimates, moving averages, and key financial metrics. The project also visualizes stock data through candlestick charts and line charts using mplfinance and matplotlib.

## Table of Contents:

Project Overview
Features
Installation
Usage
API Keys
Data Sources
Dependencies


## Project Overview:
This tool enables users to:

Fetch company profile information, including industry, sector, employees, and CEO details.
Retrieve historical stock price data and visualize it using candlestick and line charts.
Obtain earnings estimates, growth forecasts, and moving averages.
Access key financial metrics from the company's income statement and balance sheet.


## Features:
Company Profile: Retrieve basic company information like symbol, name, industry, sector, and contact details.
Stock Price Visualization: Display historical stock prices as a candlestick chart and line chart.
Earnings & Growth Estimates: Obtain earnings and growth forecasts for the current and future quarters and years.
Income Statement and Balance Sheet: Fetch financial statements and display key metrics such as revenue, operating income, net income, and total assets.
Moving Averages: Calculate and display simple moving averages (SMA).
Key Metrics: Retrieve key financial ratios and metrics over time.


## Installation:
Prerequisites:

Python 3.x
An active API key from TwelveData (https://twelvedata.com) and Financial Modeling Prep (https://financialmodelingprep.com).

Steps:

Download the script or clone the repository.
Install the required dependencies using pip:
Set your TwelveData and Financial Modeling Prep API keys in the script.


## Usage:
Run the script in your Python environment

Enter the stock ticker symbol and interval (e.g., 1 day, 1 week, etc.) when prompted:

## Output: The program will retrieve and display:

## Company profile details
Stock price charts (candlestick and line chart)
Earnings estimates and growth forecasts
Income statement, balance sheet, and key metrics
Graphs will be shown in a separate window, and financial data will be printed in the terminal.


## API Keys:
This project requires two API keys:

TwelveData API for retrieving stock prices, company profiles, earnings, and growth estimates.
Sign up at TwelveData (https://twelvedata.com) to get your API key.
Replace the placeholder key in the script with your TwelveData API key.
Financial Modeling Prep (FMP) API for financial statements and key metrics.
Sign up at Financial Modeling Prep (https://financialmodelingprep.com) to get your API key.
Replace the placeholder key2 in the script with your FMP API key.


## Data Sources:
TwelveData: Provides stock time series data, company profiles, earnings estimates, and growth forecasts.
Financial Modeling Prep: Supplies income statements, balance sheets, and key financial metrics.


## Dependencies:
The following Python libraries are required:

requests: For making API requests.
pandas: For data manipulation and handling.
matplotlib: For data visualization.
mplfinance: For generating candlestick charts.

