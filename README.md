# Investment Dashboard

A full-stack web application that scrapes real-time and historical stock & cryptocurrency prices, allows users to manage their portfolios, backtest strategies, and uses AI to predict market trends. Built with Django, React, and PostgreSQL.

## Features

### Part 1: Stock Price Scraper & Dashboard
- Scrape real-time stock prices using APIs like Yahoo Finance or Alpha Vantage.
- Store real-time and historical price data in PostgreSQL.
- Provide a Django REST API to serve price data.
- Display stock trends using a React-based dashboard with interactive charts.
- Allow users to create a watchlist to track selected stocks.

### Part 2: Expand to Crypto
- Integrate cryptocurrency price data using APIs like CoinGecko or Binance.
- Enable tracking of both stocks and cryptocurrencies.
- Add filtering/search functionality for easy navigation.

### Part 3: Portfolio Management
- Allow users to input stock/crypto holdings and track real-time portfolio value.
- Store portfolio data securely with authentication.
- Display profit/loss calculations and performance over time.
- Implement visual analytics like pie charts and line graphs.

### Part 4: Backtesting & Investment Comparisons
- Enable users to simulate investment strategies with historical data.
- Compare investment types (stocks vs. crypto vs. bonds).
- Calculate risk-adjusted returns (Sharpe ratio, volatility metrics).
- Include preset strategies (e.g., dollar-cost averaging vs. lump-sum investing).

### Part 5: AI Predictions
- Use machine learning models (TensorFlow, scikit-learn) to predict market trends.
- Display AI-generated forecasts for stock/crypto prices.
- Provide confidence intervals and trend probabilities.

### Part 6: Additional Features
- Fetche stock/crypto news and analyzes sentiment.
- Notify users of major market movements.
- Track investment discussions on Twitter, Reddit, etc.
- Help users set and track investment goals.

---

## Tech Stack

### **Backend:**
- **Django & Django REST Framework** – API backend for serving data.
- **PostgreSQL** – Database for storing stock/crypto price history.
- **Celery & Redis** – Handles background tasks like scheduled scraping.
- **BeautifulSoup & Selenium** – Web scraping tools for gathering data.

### **Frontend:**
- **React** – Interactive user interface.
- **Recharts / Chart.js** – Graphs and data visualizations.
- **Axios** – Handles API calls between frontend and backend.

### **Machine Learning (Phase 5)**
- **TensorFlow / scikit-learn** – AI-based trend prediction models.
- **NLTK / VADER** – Sentiment analysis for financial news.