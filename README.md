# Binance Futures Testnet Trading Bot

A structured Python trading application designed to place orders on the Binance Futures Testnet (USDT-M). Built with input validation using Pydantic, persistent file logging, and exception handling.

---

## 📋 Features

- **Order Types Supported**: `MARKET` and `LIMIT` orders.
- **Order Sides**: `BUY` and `SELL`.
- **Validation Layer**: Validates trading pairs (USDT-M), order sides, quantities, and required fields using Pydantic.
- **Logging**: API requests, raw responses, and execution errors are logged to `logs/bot.log`.

---

## 🛠️ Setup & Installation

### 1. Prerequisites
- Python 3.9+
- Binance Futures Testnet API Key & Secret Key

### 2. Installation
```bash
git clone [https://github.com/YOUR_USERNAME/binance-futures-trading-bot.git](https://github.com/YOUR_USERNAME/binance-futures-trading-bot.git)
cd binance-futures-trading-bot
pip install -r requirements.txt
