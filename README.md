# Stock Revenue Analysis and Dashboard

## Overview

This project demonstrates the process of collecting, cleaning, analyzing, and visualizing financial data using Python. Stock market data is retrieved through the **Yahoo Finance API (yfinance)**, while historical company revenue data is collected through **web scraping** with BeautifulSoup.

The project compares historical stock prices with company revenue trends for **Tesla** and **GameStop**, illustrating how multiple data sources can be combined to generate meaningful business insights.

This project was completed as part of the **IBM Data Analyst Professional Certificate**.

---

## Objectives

- Retrieve historical stock prices using the Yahoo Finance API
- Extract company revenue data through web scraping
- Clean and preprocess financial datasets
- Visualize stock prices and revenue trends
- Compare market performance with company financial performance

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- BeautifulSoup
- Requests
- yfinance
- Jupyter Notebook

---

## Skills Demonstrated

- API Integration
- Web Scraping
- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Financial Data Analysis
- Data Visualization
- Python Programming

---

## Project Workflow

### 1. Data Collection

Historical stock prices were extracted using:

- Yahoo Finance API (`yfinance`)

Historical quarterly revenue data was extracted using:

- BeautifulSoup
- Requests

---

### 2. Data Cleaning

The project includes:

- Removing commas and currency symbols
- Removing null values
- Removing empty observations
- Formatting dates
- Preparing datasets for visualization

---

### 3. Data Visualization

Custom visualizations compare:

- Tesla Stock Price vs Revenue
- GameStop Stock Price vs Revenue

The dashboard highlights how market performance and company revenue have changed over time.

---

## Project Structure

```
Stock-Revenue-Analysis/
│
├── Revenue Data and Building a Dashboard.py
├── README.md
└── screenshots/
    ├── tesla-dashboard.png
    ├── gamestop-dashboard.png
    ├── tesla-stock-data.png
    └── gamestop-stock-data.png
```

---

## Required Libraries

```bash
pip install pandas
pip install matplotlib
pip install beautifulsoup4
pip install requests
pip install yfinance
```

---

## Key Features
- Retrieve stock market data through APIs
- Extract financial information from HTML tables
- Clean raw financial datasets
- Compare revenue with historical stock prices
- Create publication-quality visualizations

---

## Learning Outcomes

Through this project I learned how to:

- Integrate multiple data sources
- Retrieve financial data using APIs
- Extract structured data from websites
- Clean real-world datasets
- Build comparative financial visualizations
- Communicate insights using Python

---

## Author

**Jaelyn Lane**

IBM Data Analyst Professional Certificate
