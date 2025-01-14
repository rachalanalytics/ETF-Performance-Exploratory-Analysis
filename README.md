# Analyzing ETF Performance: Short- and Long-Term Investment Strategies

## Overview

This project provides a comprehensive analysis of Exchange-Traded Funds (ETFs) to assist investors in making informed decisions. By leveraging data from Yahoo Finance, the project identifies ETFs with:

1. **High short-term growth potential**: Using metrics like quarterly returns, volatility, and momentum.
2. **Long-term stability**: Analyzing 200-day moving averages and historical volatility.
3. **Balanced growth and risk**: Combining returns, volatility, and drawdown for a solid risk-return profile.

The project includes automated data scraping, cleaning, exploratory data analysis (EDA), and advanced visualizations.

---

## Features

- **Automated Data Collection**:
  - Scrapes ETF data from [Yahoo Finance](https://finance.yahoo.com/markets/etfs/most-active).
  - Gathers additional metrics (volatility, dividend yield) using Yahoo Finance's API.

- **Comprehensive Data Cleaning**:
  - Handles missing values, standardizes formats, and ensures accurate analysis.

- **Exploratory Data Analysis**:
  - Visualizations of price distributions, returns, and correlations.
  - Identification of top-performing ETFs for both short- and long-term strategies.

- **Advanced Insights**:
  - Interactive scatter plot to visualize growth vs. risk for ETFs.
  - Highlights the ETF with the best growth-to-risk ratio.

---

## Technologies Used

- **Python**:
  - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `selenium`, `beautifulsoup4`, `yfinance`.
- **Data Sources**:
  - Yahoo Finance.

---

## Getting Started

### Prerequisites

Ensure the following are installed in your environment (the code block for these are included in the file):

!pip install --upgrade gspread gspread-dataframe pandas
!pip install plotly

!pip install selenium
!apt update # Update package lists
!apt install chromium-chromedriver # Install chromium and the driver

## Future Enhancements

While this project provides actionable insights, there are opportunities to extend its functionality:
- Incorporate additional financial metrics, such as the Sharpe ratio and beta, for more comprehensive analysis.
- Implement backtesting to evaluate historical performance of selected ETFs.
- Enhance modularity by refactoring code into reusable functions for easier maintenance and scalability.
- Include deeper analysis on dividend yield and use predictive models to optimize a trading portfolio.
