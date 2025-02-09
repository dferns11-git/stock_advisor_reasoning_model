# AI-Powered Stock Analysis & Dividend Tracker

This project is a **Gradio-powered AI stock analysis tool** that helps you make smarter investment decisions by providing real-time stock data, AI-driven recommendations, and dividend yield insights. It pulls data from Yahoo Finance, uses OpenAI's o1-mini model for analysis, and generates interactive plots to visualize dividend payouts versus stock prices.

## Features

- **Real-time stock and ETF data** from Yahoo Finance.
- **AI-driven buy/hold/sell recommendations** using OpenAI's o1-mini reasoning models.
- **Dividend yield calculations & insights** to help evaluate stock performance.
- **Interactive dividend vs. stock price plots** using Plotly for better decision-making.

## How It Works

1. **Enter a stock or ETF ticker symbol** (e.g., AAPL, TSLA, SPY).
2. The system fetches key stock data, including sector, previous close, and dividend yield.
3. **AI provides a quantitative recommendation** based on valuation, market trends, and volatility.
4. View a **dynamic Plotly graph** of dividend payouts vs. stock prices.

## Tech Stack

- **Python + Gradio** for the web interface.
- **Yahoo Finance API** for real-time stock data.
- **OpenAI's o1-mini reasoning models** for intelligent analysis.
- **Plotly** for interactive financial visualizations.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/ai-stock-analysis.git
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the app:
    ```bash
    python app.py
    ```

## Usage

- Enter any stock or ETF ticker symbol to see real-time data and get AI-based investment recommendations.
- View interactive plots comparing dividends and stock prices.
