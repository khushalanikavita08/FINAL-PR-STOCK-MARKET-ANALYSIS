# STOCK-MARKET-ANALYSIS
<div align="center">

# 📈 Stock Market Analysis & Visualization Dashboard

### *"Numbers tell stories that words often can't."* 🕯️

<br>

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![yfinance](https://img.shields.io/badge/yfinance-Data%20Source-00C853?style=for-the-badge&logo=yahoo&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Plots-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-ff69b4?style=for-the-badge)

<br>

<!-- LIVE / ANIMATED SECTION -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=00C9A7&center=true&vCenter=true&width=650&lines=Live+Stock+Market+Analysis+%F0%9F%93%88;Tracking+RELIANCE.NS+in+Real-Time;Trend+%2B+Volatility+%2B+Correlation;Powered+by+Python+%F0%9F%90%8D" alt="Typing SVG" />

<br><br>

![Live Stock Ticker](https://raw.githubusercontent.com/gadhagod/stock-widget-images/main/graph.gif)

</div>

---

## 📚 Menu

- [Project Overview](#-project-overview)
- [Live Market Snapshot](#-live-market-snapshot)
- [Key Features](#-key-features)
- [Project Structure](#️-project-structure)
- [Tech Stack](#️-tech-stack)
- [Getting Started](#-getting-started)
- [Configuration](#️-configuration)
- [Sample Output](#-sample-output)
- [Roadmap](#-roadmap)
- [FAQ](#-faq)
- [Feedback](#-feedback)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🧠 Project Overview

This is an **end-to-end stock market analysis tool** built in Python that downloads real market data through the `yfinance` API and transforms it into professional-grade, publication-ready visualizations. It automatically calculates moving averages, daily returns, and rolling volatility, then generates four clean charts — trend, volume, return distribution, and correlation — so you can go from raw ticker data to actionable insight in a single run.

Whether you're a student learning quantitative finance, a hobbyist tracking your favorite stock, or someone prototyping a bigger trading system, this project gives you a solid, ready-to-extend foundation.

---

## ⚡ Live Market Snapshot

> 📡 Every time this project runs, it pulls **live** market data straight from the yfinance API — no static or outdated numbers, just fresh prices, volumes, and trends fetched directly from the exchange.

<div align="center">

[![Live Chart](https://img.shields.io/badge/📊_Live_Chart-View_on_TradingView-131722?style=for-the-badge&logo=tradingview&logoColor=white)](https://www.tradingview.com/symbols/NSE-RELIANCE/)
[![Live Price](https://img.shields.io/badge/💹_Live_Price-Yahoo_Finance-720E9E?style=for-the-badge&logo=yahoofinance&logoColor=white)](https://finance.yahoo.com/quote/RELIANCE.NS)

</div>

---

## ✨ Key Features

- 📥 **Live Data Fetching** — Real-time and historical stock data via the yfinance API
- 📊 **Moving Averages** — SMA 20, SMA 50, and EMA 20 calculated automatically
- 📈 **Price Trend Visualization** — Combined chart of closing price with moving averages
- 📉 **Volume Analysis** — Time-series bar chart of trading volume
- 🎯 **Daily Returns Distribution** — Histogram + KDE curve to understand return patterns
- 🔥 **Correlation Heatmap** — Relationship between price, volume, returns, and MAs
- 🧮 **Volatility Tracking** — 20-day rolling volatility calculation
- 🖼️ **Auto-Saved Charts** — All plots are automatically saved as high-res PNG files
- 🧹 **Clean Data Pipeline** — Built-in missing value handling and MultiIndex flattening
- 🔁 **Ticker-Agnostic** — Works with any valid stock symbol, not just one company
- 🧾 **Quick Statistics** — Descriptive stats (mean, std, min/max) printed to console

---

## 🗂️ Project Structure

```
stock-analysis-dashboard/
│
├── 📄 stock_analysis.py              # Main script — data fetch + analysis + plots
├── 📊 price_trend_with_moving_averages.png
├── 📊 trading_volume.png
├── 📊 daily_returns_distribution.png
├── 📊 correlation_heatmap.png
├── 📄 requirements.txt               # Project dependencies
├── 📄 README.md                      # You are here 👋
└── 📄 LICENSE                        # MIT License
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| 🐍 Python | Core programming language |
| 📦 yfinance | Live stock market data fetching |
| 🐼 Pandas | Data manipulation & feature engineering |
| 🔢 NumPy | Numerical computations |
| 🎨 Matplotlib | Base plotting engine |
| 🌊 Seaborn | Statistical visualizations |

---

## 🚀 Getting Started

### ✅ Prerequisites
- Python 3.9 or higher
- Internet connection (required for live data fetching)

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/stock-analysis-dashboard.git
cd stock-analysis-dashboard
```

### 2️⃣ Install dependencies
```bash
pip install yfinance pandas numpy matplotlib seaborn
```

### 3️⃣ Run the script
```bash
python stock_analysis.py
```

### 4️⃣ Output
As soon as the script finishes, 4 charts will be saved automatically in the current folder 🎉

---

## ⚙️ Configuration

You can analyze any stock by changing these values at the top of the script:

```python
TICKER = "RELIANCE.NS"
START_DATE = "2020-01-01"
END_DATE = "2024-12-31"
```

> 💡 Tip: Use the correct exchange suffix for non-US stocks — e.g. `.NS` for NSE (India), `.BO` for BSE, `.L` for London Stock Exchange.

---

## 📸 Sample Output

<div align="center">

| Price Trend | Volume Analysis |
|:---:|:---:|
| 📈 SMA/EMA overlay chart | 📊 Volume bar chart |

| Returns Distribution | Correlation Heatmap |
|:---:|:---:|
| 📉 Histogram + KDE | 🔥 Correlation matrix |

</div>

---

## 🗺️ Roadmap

- [ ] Add interactive charts using Plotly
- [ ] Support multi-stock comparison in a single run
- [ ] Add RSI, MACD, and Bollinger Bands indicators
- [ ] Export analysis as a PDF report
- [ ] Build a simple Streamlit web dashboard

---

## ❓ FAQ

**Q: Does this work for stocks outside India?**
Yes — just change the `TICKER` to any valid Yahoo Finance symbol (e.g. `AAPL`, `TSLA`, `GOOGL`).

**Q: Why is my data empty?**
Usually caused by an invalid ticker symbol or no internet connection during the API call.

---

## 💬 Feedback

If you have any suggestions or ideas for improvement, please open an issue — every bit of feedback helps make this project better! 🙌
Real-world use cases from users are exactly what motivate new features to get built. 💡

---

## 🤝 Contributing

Contributions are always welcome — fork it, make your changes, and send a PR! 🚀
For bigger changes, opening an issue first to discuss is usually the better approach. 🧩

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

<div align="center">

### *"Markets move in cycles — so does growth. Keep analyzing, keep learning."* 🌱

<br>

![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red?style=for-the-badge)
![Python Powered](https://img.shields.io/badge/Powered%20by-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Open Source](https://img.shields.io/badge/Open%20Source-💚-brightgreen?style=for-the-badge)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-orange?style=for-the-badge)

⭐ **If you found this project useful, consider giving it a star!** ⭐

</div>
