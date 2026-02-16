# Crypto Hub - Machine Learning Price Prediction Platform

A comprehensive cryptocurrency platform featuring:
- ML-powered price prediction
- Real-time cryptocurrency listings
- Currency converter
- Crypto news feed

## Features

1. **Price Prediction**: Machine learning models to predict cryptocurrency prices
2. **Crypto Listings**: Display all major cryptocurrencies with real-time data
3. **Currency Converter**: Convert between different cryptocurrencies
4. **News Feed**: Latest cryptocurrency news and market updates

## Installation

1. Install Python 3.8 or higher
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env
   ```
   Add your API keys to the .env file

## Usage

Run the application:
```bash
python app.py
```

Open your browser and navigate to `http://localhost:8050`

## API Keys Required

- NewsAPI key for crypto news
- CoinGecko API (free tier available)

## Project Structure

```
crypto-hub/
├── app.py                 # Main Dash application
├── models/               # ML models
├── data/                 # Data processing
├── pages/                # Individual pages
├── utils/                # Utility functions
└── requirements.txt      # Dependencies
```



