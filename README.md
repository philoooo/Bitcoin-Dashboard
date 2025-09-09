#  Bitcoin Price Data Analysis Dashboard

An interactive data dashboard built with Python and Streamlit for visualizing and analyzing historical Bitcoin price trends.

---

##  Live Demo

👉 [Launch the Live Dashboard](https://bitcoin-dashboard-dtznn7khfnjeffywsnptk5.streamlit.app/)

---

##  Project Overview

This project explores and visualizes Bitcoin price data using a variety of analytical and plotting tools. It includes:

-  Interactive candlestick chart for the first 100 days
-  Daily percentage change in closing price
-  Line charts of Open, High, Low, Close prices over time
-  Yearly, quarterly, and monthly average close price trends
-  Comparison of closing price on normal vs. log scale

The dashboard allows users to interactively explore Bitcoin trends, making it suitable for people interested in crypto financial data.

---

##  Dataset

- **File Used**: `bitcoin_price_Training - Training.csv`


---

##  Tools & Libraries Used

- **Languages**: Python 3.x
- **IDE**: [Spyder](https://www.spyder-ide.org/)
- **Packages**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `plotly`
  - `streamlit`

---

## How I Built This Project

This project was developed in four main phases to transform raw data into an interactive analytical tool.

### 1. Understanding the Use Case

Bitcoin price analysis can help investors and traders interpret market fluctuations and long-term trends. The goal was to provide an accessible, visual way to explore these patterns using a historical time-series dataset.

I started with a CSV file containing daily Bitcoin price data, including Open, High, Low, Close, and Volume metrics along with timestamps.

### 2. Data Preprocessing

Using Python (Pandas and NumPy), I prepared the dataset by:

- Checking for and handling missing values
- Removing duplicate records
- Converting the `Date` column to datetime format
- Sorting the dataset chronologically
- Resetting and setting the datetime index for proper time-series alignment

This ensured the dataset was structured and analysis-ready.

### 3. Exploratory Data Analysis

Key analytical steps included:

- **Trend Analysis**: Visualized Open, High, Low, and Close price movements over time using line charts.
- **Volatility Analysis**: Calculated and plotted daily percentage change in the closing price to understand short-term market swings.
- **Candlestick Visualization**: Created a candlestick (OHLC) chart for the first 100 days to provide detailed insight into short-term trends.

### 4. Dashboard Development

The final step was transforming the analysis into an interactive dashboard using Streamlit and Plotly. Features include:

- Candlestick chart (OHLC) for the first 100 days of Bitcoin data
- Line chart of daily percentage change in closing price
- Dynamic dropdown to view Open, High, Low, or Close prices over time
- Yearly, quarterly, and monthly average closing price visualizations
- Comparison of closing price trends on normal vs. logarithmic scale

This dashboard allows users to interact with the data in real time, providing a comprehensive view of Bitcoin’s historical behavior.

---
