# IBM_Python-Project-for-Data-Science
Analyzed Tesla and GameStop stock performance using Python, yfinance, and web scraping. Extracted and cleaned financial data with Pandas and BeautifulSoup, then visualized stock price and revenue trends using Matplotlib.


# 📊 Stock Market Analysis: Tesla & GameStop

## 🚀 Project Overview

Built an end-to-end financial data analysis workflow to examine **Tesla (TSLA) and GameStop (GME)** stock performance and quarterly revenue trends using Python. Integrated financial data extraction, web scraping, data cleaning, and visualization to transform raw data into meaningful financial insights.

## 🎯 Business Objectives

- Analyze historical stock price movements and quarterly revenue trends.
- Extract financial data from APIs and HTML webpages.
- Clean and transform unstructured revenue data into analysis-ready datasets.
- Visualize stock performance alongside revenue trends to support data-driven interpretation.

## 🛠️ Tech Stack

**Python | Pandas | yfinance | Requests | BeautifulSoup | Matplotlib | Jupyter Notebook**

## 🔍 Project Workflow

### 1. Financial Data Extraction
- Retrieved historical stock market data for Tesla and GameStop using `yfinance`.
- Extracted quarterly revenue data from webpages using `Requests` and `BeautifulSoup`.

### 2. Data Cleaning & Transformation
- Removed currency symbols, commas, empty strings, and missing revenue values.
- Structured raw financial data into clean Pandas DataFrames.
- Prepared datasets for analysis and visualization.

### 3. Data Visualization
- Developed stock price and revenue visualizations using Matplotlib.
- Used a reusable `make_graph()` function to present historical stock performance alongside quarterly revenue.
- Compared financial trends across Tesla and GameStop.

## 📁 Project Structure

- `Extracting Stock Data Using a Python.ipynb` — Historical stock data extraction.
- `Extracting Stock Data Using Web Scraping.ipynb` — Revenue extraction using web scraping.
- `Analyzing Historical StockRevenue Data and Building a Dashboard.ipynb` — Data preparation and stock-revenue visualization.

## 💡 Key Skills Demonstrated

- Financial Data Analysis
- Web Scraping & Data Extraction
- Data Cleaning & Preprocessing
- Exploratory Data Analysis
- Data Visualization & Trend Analysis
- Python-Based Analytical Workflows

## ⚙️ Getting Started

Install the required libraries:

```bash
pip install yfinance pandas requests beautifulsoup4 html5lib matplotlib lxml
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks and execute the cells sequentially. An internet connection is required to retrieve online data.

## 📌 Key Takeaway

Demonstrates the ability to collect financial data from multiple sources, transform raw information into structured datasets, and communicate historical stock and revenue trends through visualizations.

**Data coverage:** The supplied visualizations focus on historical data through June 2021; they do not represent current market conditions.

## ⚠️ Disclaimer

For educational and portfolio purposes only. This project does not provide investment advice.

## 🙏 Acknowledgement

Inspired by the IBM Developer Skills Network stock data analysis project.
