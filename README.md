# Analyzing Historical Stock and Revenue Data

This project extracts, cleans, and visualizes historical stock price and quarterly revenue data for Tesla (TSLA) and GameStop (GME) using Python. It demonstrates how financial and revenue data can be combined to provide insights into company performance.

## Features

- Fetches historical stock data using the `yfinance` library.
- Scrapes quarterly revenue data from Macrotrends website with `requests` and `BeautifulSoup`.
- Cleans and preprocesses data for accurate analysis.
- Visualizes stock prices and revenue trends with interactive Plotly graphs.
- Provides a comparative dashboard to analyze stock performance against revenue.

## Installation

Make sure you have the following Python libraries installed:

```bash
pip install yfinance pandas requests beautifulsoup4 plotly
Usage
Run the Python scripts or Jupyter notebook cells sequentially to:

Download Tesla and GameStop stock data.

Scrape and clean quarterly revenue data.

Generate interactive plots comparing stock prices and revenues.

Use the provided make_graph() function to visualize the data.

Example
python
Copy
Edit
make_graph(tesla_data, tesla_revenue, "Tesla (revenue vs. price comparison)")
make_graph(gme_data, gme_revenue, "GameStop (revenue vs. price comparison)")
Project Structure
stock_data_extraction.py - Scripts to download stock data using yfinance.

revenue_scraping.py - Web scraping scripts to get revenue data.

visualization.ipynb - Jupyter notebook with analysis and interactive graphs.

License
This project is licensed under the MIT License.
