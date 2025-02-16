# Disclaimer

This project is in the early stages of development and is evolving into an Algorithmic Trading system. Currently, the focus is on market analysis using various data sources and tools, with plans for future enhancements towards building a fully functional trading algorithm. The project is intended for educational and research purposes and should not be considered a complete solution for trading at this stage.

# Algorithmic Stock Analysis and Trading

This repository contains Python-based tools and algorithms for analyzing and trading stocks using **yfinance** and the **NSE API**. The project leverages various datasets and methods to provide insights into stock trends, index movements, and delisted securities.

---

## Folder and File Structure

### 1. **Sample Programs**
   - Contains example Jupyter notebooks (`Algo_1_Samples`, `Algo_2_Samples`) demonstrating the core functionality of stock analysis algorithms.

### 2. **Stock Details**
   - **`BSE_stocks.json`**: JSON file listing details of stocks listed on the Bombay Stock Exchange.
   - **`NSE_stocks.json`**: JSON file containing stock data for the National Stock Exchange.
   - **`data(safety).txt`**: A data safety-related text file (possibly metadata or notes).
   - **`delisted_stocks(original_copy).csv`**: Details of delisted stocks for reference.
   - **`EQUITY_L.csv`**: Equity stock-related data for broader analysis.
   - **`List_of_companies.csv`**: List of companies for sector-wise or company-specific insights.
   - **`Yahoo Finance Stock Codes.xlsx`**: Excel sheet containing stock codes for fetching data from Yahoo Finance.

### 3. **Stock Analysis**
   - **`daily_results/`**: Directory for storing daily analysis outputs.
   - **`stock_lists/`**: Contains stock lists used for targeted analysis.

### 4. **Stock Index Analysis**
   - **`index_stocks_analysis_*.csv`**: CSV files providing historical index-wise stock analyses.

### 5. **Jupyter Notebooks**
   - **`A2_Sample1.ipynb`**: Notebook showcasing detailed algorithm execution and analysis.
   - **`Algo_1.ipynb`**: Implements the first algorithm for stock analysis.
   - **`nseindia.ipynb`**: A notebook for interacting with and analyzing data from the NSE API.
   - **`MW-All-Indices-23-Jan-2025.csv`**: Dataset containing stock market indices for a specific date.

---

## Features

1. **Stock Market Data Analysis**
   - Analyze stocks listed on BSE and NSE.
   - Handle delisted stocks and equity-related data.
   - Access Yahoo Finance and NSE APIs for real-time and historical data.

2. **Index and Daily Trends**
   - Perform index-wise stock analysis.
   - Store daily analysis results for tracking trends.

3. **Algorithmic Trading**
   - Demonstrates the application of algorithms to identify trading opportunities.

---

## Prerequisites

- Python 3.8 or above
- Libraries: `pandas`, `numpy`, `yfinance`, `matplotlib`, `seaborn`, and any additional requirements in your notebooks.

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/pranai11/ALGO_TRADING.git
   cd ALGO_TRADING
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Explore the notebooks for a step-by-step understanding of the algorithms.

---

## Disclaimer

This project is for educational purposes only. Use the provided data and algorithms responsibly and in compliance with applicable regulations. **This is not financial advice.**

---
