# Python Project for Data Science

This repository contains a data science project focused on analyzing historical stock and revenue data for selected companies using Python. The project is organized into a structured workflow for data extraction, cleaning, and visualization.

## Project Structure

```
Python Project for Data Science/
└── Analyzing Historical Stock/Revenue Data and Building a Dashboard/
    ├── ES - Extracting and Visualizing Stock Data.ipynb
    ├── ES - Extracting Stock Data Using a Python Library.ipynb
    └── ES - Extracting Stock Data Using a Web Scraping.ipynb
```

## File Descriptions

### 📓 ES - Extracting and Visualizing Stock Data.ipynb
This notebook focuses on **visualizing stock and revenue data** using Matplotlib. It includes:
- Data merging between stock price history and revenue
- Line plots for stock prices and revenue trends
- Combined visualizations for insights

### 📓 ES - Extracting Stock Data Using a Python Library.ipynb
This notebook demonstrates **how to extract stock data using the `yfinance` Python library**. It includes:
- Downloading historical data for Tesla (TSLA) and GameStop (GME)
- DataFrame manipulations and cleaning
- Data preview and structure validation

### 📓 ES - Extracting Stock Data Using a Web Scraping.ipynb
This notebook showcases **web scraping techniques using BeautifulSoup** to extract historical revenue data from static HTML pages. It includes:
- HTTP requests and HTML parsing
- Extracting tables from Tesla and GameStop revenue pages
- Data cleaning and conversion for further analysis

## Technologies Used
- Python
- Jupyter Notebook
- pandas
- yfinance
- BeautifulSoup
- matplotlib

## Setup

Install the required libraries if not already available:

```bash
pip install yfinance beautifulsoup4 html5lib matplotlib pandas
```

## License
This project is part of the IBM Data Science Certification coursework and is intended for educational purposes only.
