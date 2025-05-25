# 📊 Multi-Asset ETF Analysis with Python

Analyze and compare the performance of major ETFs (SPY, QQQ, GLD, ^VIX) using Python. This project explores price trends, volatility, moving averages, and overall returns to draw key investment insights.

---

## 📁 Project Structure

```
📦 stock_analysis/
├── Stock_Analysis.ipynb        # Jupyter notebook with full analysis
├── img/                        # Output plots and visualizations
│   ├── spy_closing_price.png
│   ├── spy_volume.png
│   ├── spy_moving_averages_multi.png
│   ├── qqq_moving_averages.png
│   ├── gld_moving_averages.png
│   ├── etf_comparison_normalized.png
│   └── etf_kpi_summary.png
```

---

## 🧰 Tech Stack & Libraries

* Python 3
* pandas, numpy
* yfinance
* matplotlib, seaborn
* Jupyter Notebook

---

## 📈 ETFs Analyzed

| Ticker | Description             |
| ------ | ----------------------- |
| SPY    | S\&P 500 Index ETF      |
| QQQ    | Nasdaq 100 ETF          |
| GLD    | Gold Trust (Commodity)  |
| ^VIX   | Volatility Index (CBOE) |

---

## 🧠 Key Features

* Pull and structure financial data using `yfinance`
* Calculate and plot moving averages (SMA, EMA)
* Compare normalized performance of multiple assets
* Generate visual KPI summary: return %, volatility, current price
* Draw meaningful investment insights and patterns

---

## 📌 Key Insights

* **QQQ** significantly outperformed all other ETFs with a **+1157% return**, driven by the explosive growth of tech stocks since 2010.
* **SPY**, representing the broader S\&P 500, delivered a solid **+575% return**, making it a reliable benchmark for long-term equity investing.
* **GLD** showed a consistent, defensive performance of **+182%**, with lower volatility, highlighting its role as a hedge in uncertain markets.
* **^VIX**, the volatility index, exhibited extreme annual volatility (**132%**) and modest growth. It is not an investment vehicle but a crucial **market fear indicator**.
* Moving averages (SMA and EMA) helped visualize market phases, with QQQ and SPY showing long-term bullish trends, and GLD highlighting cyclical movements aligned with macroeconomic stress.

> This multi-asset analysis provides valuable insights into portfolio diversification, risk exposure, and market behavior across different asset classes.

---

## ▶️ How to Run It

1. Clone this repo:

```bash
git clone https://github.com/agusij/stock_analysis.git
cd stock_analysis
```

2. Create a virtual environment and install requirements:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt  # or install manually
```

3. Run the notebook:

```bash
jupyter notebook Stock_Analysis.ipynb
```

---

## 📬 Contact

* GitHub: [@agusij](https://github.com/agusij)
* LinkedIn: [Agustín Jaureguiberry](https://linkedin.com/in/aijaureguiberry)

> Created as part of a data analyst portfolio to demonstrate financial analysis, visualization, and Python automation skills.
