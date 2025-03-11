** In Progress **

Volatility Cone Analysis

Introduction
This project is a CLI-based tool designed to analyze the historical volatility of individual stocks or index constituents using volatility cone analysis. It retrieves stock data from Yahoo Finance, filters securities based on market capitalization and daily turnover, and calculates historical volatilities over various time periods.

Features
Stock Data Retrieval: Fetches up to 5 years of historical stock data using yfinance.
Filtering Mechanism: Filters stocks based on market cap and daily turnover to focus on relevant securities.
Volatility Calculation: Computes rolling volatilities for different timeframes (10-day, 30-day, 60-day, 90-day, 180-day, 360-day).
User Input Support: Allows users to input a stock ticker and filter parameters interactively.
CLI-Based: Simple command-line interface for quick analysis.

Usage
Users can run the script and provide a stock ticker, market cap range, and turnover range. The program will then fetch, filter, and analyze the stock's historical volatility.
