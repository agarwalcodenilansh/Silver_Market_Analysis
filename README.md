# 🥈 Silver Market Analysis (2016–2026)
### Comprehensive Technical & Macroeconomic Analysis of the Silver Market

> A data-driven analysis of silver price dynamics across 2,534 trading days — covering price trends, technical indicators, gold-silver ratio dynamics, volatility modeling, and macroeconomic correlations.

---

![Period](https://img.shields.io/badge/Period-Jan%202016%20–%20Jan%202026-silver)
![Trading Days](https://img.shields.io/badge/Trading%20Days-2%2C534-blue)
![Current Price](https://img.shields.io/badge/Current%20Price-%24113.11-brightgreen)
![Best Year](https://img.shields.io/badge/Best%20Year-2025%20%2B136.76%25-orange)
![Report Date](https://img.shields.io/badge/Report%20Date-February%202%2C%202026-lightgrey)

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Key Statistics](#key-statistics)
- [Analysis Modules](#analysis-modules)
  - [Price Trend Analysis](#price-trend-analysis)
  - [Gold vs Silver Comparative Performance](#gold-vs-silver-comparative-performance)
  - [Gold-Silver Ratio Dynamics](#gold-silver-ratio-dynamics)
  - [Technical Indicators](#technical-indicators)
  - [Volatility Analysis](#volatility-analysis)
  - [Macroeconomic Relationships](#macroeconomic-relationships)
  - [Historical Annual Returns](#historical-annual-returns)
- [Investment Implications](#investment-implications)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Disclaimer](#disclaimer)

---

## Project Overview

This project delivers a comprehensive quantitative analysis of silver market behavior from January 2016 to January 2026. The analysis integrates price data, technical indicators, and macroeconomic variables to characterize silver's evolving role as both an industrial commodity and a monetary asset.

The silver market underwent a structural transformation during the analysis window — from a range-bound commodity trading between $15–18 (2016–2019), through a pandemic-driven rally in 2020, to an unprecedented bull run in 2025 that pushed prices past $113 per troy ounce. This project quantifies that transformation with rigorous statistical and technical analysis.

**Analyst:** Nilansh Agarwal  
**Report Date:** February 2, 2026

---

## Dataset

**File:** `Silver_Project_Data.xlsx`

| Column | Description |
|---|---|
| `Date` | Trading date |
| `USD_Index` | US Dollar Index (DXY) |
| `Gold` | Gold spot price (USD) |
| `Silver` | Silver spot price (USD/troy oz) |
| `Gold_Silver_Ratio` | Gold price ÷ Silver price |
| `Silver_Daily_Return` | Daily percentage return of silver |
| `RSI` | 14-day Relative Strength Index |
| `SMA50` | 50-day Simple Moving Average |
| `SMA200` | 200-day Simple Moving Average |
| `Month` | Month of observation |
| `Daily_Return` | Raw daily return |
| `Returns` | Cumulative/rolling returns |
| `Anomaly` | Anomaly flag (binary) |
| `Prev_Silver` | Previous day's silver price |

**Coverage:** 2,534 trading days · January 4, 2016 – January 28, 2026

---

## Key Statistics

| Metric | Value |
|---|---|
| 📅 Analysis Period | Jan 4, 2016 – Jan 28, 2026 |
| 📊 Total Trading Days | 2,534 |
| 💵 Current Silver Price | $113.11 |
| 📈 Average Silver Price | $23.02 |
| 📉 Minimum Price | $11.73 (March 2020) |
| 🏆 Maximum Price | $115.08 |
| 📐 Price Std. Deviation | $9.87 |
| 🔄 Current Gold-Silver Ratio | 46.87 |
| 📊 Average Gold-Silver Ratio | 81.24 |
| 📅 Average Daily Return | 0.102% |
| ⚡ Daily Return Volatility | 1.94% |
| 🚀 Best Year | 2025: **+136.76%** |
| 📆 YTD 2026 Performance | **+60.31%** |

---

## Analysis Modules

### Price Trend Analysis

The ten-year silver price trajectory reveals four distinct market phases:

| Phase | Period | Price Range | Characteristic |
|---|---|---|---|
| Range-Bound | 2016–2019 | $13–18 | Low volatility, sideways consolidation |
| Pandemic Rally | 2020 | $12 → $26 | COVID-driven safe-haven demand |
| Correction & Consolidation | 2021–2023 | $22–24 | Profit-taking, range compression |
| Bull Run | 2024–2026 | $24 → $115 | Structural break, exponential growth |

The exponential growth phase beginning in late 2024 represents a structural break from all prior historical price patterns.

---

### Gold vs Silver Comparative Performance

Silver and gold share strong positive correlation (r = **0.923**), but diverge meaningfully in bull phases due to silver's dual industrial-monetary nature.

During the 2025 rally, silver significantly outperformed gold on a percentage basis, driven by:
- Smaller market capitalization (greater responsiveness to capital inflows)
- Heightened industrial demand from solar energy, EVs, and electronics
- Monetary safe-haven demand compounding industrial tailwinds

This outperformance compressed the gold-silver ratio to multi-decade lows.

---

### Gold-Silver Ratio Dynamics

The gold-silver ratio is a key relative-value metric for precious metals investors.

| Metric | Value |
|---|---|
| Historical Average (analysis period) | 81.24 |
| Peak (March 2020 — pandemic stress) | **125.89** |
| Current Level | **46.87** |
| 10-Year Low | 44.14 |

The current ratio near the 10-year floor raises three interpretations:
1. Silver has become relatively expensive versus gold
2. Silver is catching up from long-term historical undervaluation
3. Industrial demand fundamentals are driving silver independently of gold

Historical analysis indicates extreme ratio levels often precede mean reversion — a key metric for pair-trading strategies.

---

### Technical Indicators

#### RSI (Relative Strength Index)

- **Overbought threshold:** RSI > 70
- **Oversold threshold:** RSI < 30
- RSI proved especially useful for identifying reversal points during 2016–2020
- The 2025 bull market demonstrated that sustained uptrends can maintain elevated RSI readings for extended periods
- Current readings approaching overbought territory suggest short-term caution

#### Moving Averages (SMA 50 & SMA 200)

| Signal | Description |
|---|---|
| **Golden Cross** | SMA50 crosses above SMA200 → bullish momentum |
| **Death Cross** | SMA50 crosses below SMA200 → bearish conditions |
| **Current Config** | Price trading well above both SMAs → strong uptrend confirmed |

During the 2025 rally, the 50-day SMA consistently provided dynamic support during pullbacks, offering tactical entry points within the broader trend.

---

### Volatility Analysis

**30-Day Rolling Volatility** reveals classic volatility clustering behavior:

| Event | Volatility Impact |
|---|---|
| March 2020 (Pandemic) | Peak volatility spike |
| 2025 Bull Run | Second major volatility expansion |
| Mean Rolling Volatility | **1.7388** |

- Daily return distribution shows **slight positive skewness** — more frequent large upside moves than downside crashes
- Volatility clustering consistent with financial assets broadly: calm periods punctuated by volatility explosions
- Current volatility elevated by historical standards, indicating continued active price discovery

---

### Macroeconomic Relationships

#### Correlation Matrix

| Variable Pair | Correlation |
|---|---|
| Silver ↔ Gold | **+0.923** |
| Silver ↔ USD Index | **-0.190** |
| Gold ↔ USD Index | **+0.132** |
| Silver ↔ Gold-Silver Ratio | **-0.190** |
| RSI ↔ Silver | **+0.217** |

Silver typically exhibits an inverse relationship with the USD Index — a weaker dollar reduces the cost of dollar-denominated assets for foreign buyers and signals inflationary pressure.

**Notable anomaly:** The 2025-2026 silver surge occurred despite a relatively *stable* USD Index, suggesting fundamental demand factors and structural shifts beyond simple dollar weakness are driving prices.

---

### Historical Annual Returns

| Year | Start Price | End Price | Annual Return |
|---|---|---|---|
| 2016 | $13.82 | $15.94 | **+15.34%** |
| 2017 | $16.36 | $17.06 | +4.30% |
| 2018 | $17.12 | $15.43 | -9.86% |
| 2019 | $15.54 | $17.83 | +14.71% |
| 2020 | $17.97 | $26.33 | **+46.57%** |
| 2021 | $27.28 | $23.33 | -14.50% |
| 2022 | $22.79 | $23.86 | +4.70% |
| 2023 | $24.06 | $23.85 | -0.86% |
| 2024 | $23.73 | $28.94 | +21.94% |
| 2025 | $29.62 | $70.13 | 🚀 **+136.76%** |
| 2026 YTD | $70.56 | $113.11 | **+60.31%** |

The 2025 return of **+136.76%** is the strongest annual performance in the dataset and ranks among the best precious metals performances in modern financial history.

---

## Investment Implications

### ⚠️ Risk Factors

- **Parabolic price risk:** Dramatic 2025-2026 appreciation raises sustainability concerns; parabolic moves historically end in sharp corrections
- **Economic sensitivity:** Silver's industrial component creates exposure to global recession risk
- **Gold-silver ratio reversion:** Current compressed ratio (46.87) could revert toward the historical mean (81.24), implying silver underperformance even in a broad precious metals bull market
- **Regulatory risk:** Policy changes on taxation, margin requirements, or ownership could impact liquidity

### ✅ Opportunities

- **Industrial megatrends:** Solar energy, EVs, 5G infrastructure, and medical applications provide structural demand support independent of monetary factors
- **Monetary policy tailwinds:** Loose fiscal/monetary conditions support precious metals as inflation hedges
- **Technical momentum:** Price trading above both moving averages confirms intact uptrend; pullbacks to SMA50 offer tactical entry
- **Catch-up thesis:** If ratio compression reflects structural re-pricing of silver's industrial value, further outperformance vs gold is possible

### 📋 Recommendations by Investor Type

| Investor Type | Strategy |
|---|---|
| **Long-Term Investors** | Dollar-cost average; treat 20-30% corrections as opportunities; size positions per volatility tolerance |
| **Active Traders** | Monitor RSI + SMA signals; use SMA50 pullbacks as entries; take partial profits at overbought extremes |
| **Portfolio Managers** | 3-8% allocation as inflation hedge + industrial growth play; pair with gold to manage ratio risk |
| **Risk Management** | Use stop-loss orders or options; avoid excessive leverage; monitor macro developments actively |

---

## Project Structure

```
silver-market-analysis/
│
├── data/
│   └── Silver_Project_Data.xlsx      # Raw market data (2,534 trading days)
│
├── reports/
│   └── Silver_Market_Report.pdf      # Full executive report (Feb 2, 2026)
│
├── notebooks/
│   └── silver_analysis.ipynb         # Analysis notebook (EDA, charts, stats)
│
├── charts/                           # Exported visualizations
│   ├── price_trend.png
│   ├── gold_silver_comparison.png
│   ├── gold_silver_ratio.png
│   ├── rsi.png
│   ├── moving_averages.png
│   ├── volatility.png
│   ├── usd_correlation.png
│   ├── correlation_matrix.png
│   └── annual_returns.png
│
└── README.md
```

---

## Getting Started

### Prerequisites

```bash
pip install pandas openpyxl matplotlib seaborn scipy numpy jupyter
```

### Run the Analysis

```bash
# Clone the repository
git clone https://github.com/yourusername/silver-market-analysis.git
cd silver-market-analysis

# Launch Jupyter notebook
jupyter notebook notebooks/silver_analysis.ipynb
```

### Quick Data Load

```python
import pandas as pd

df = pd.read_excel('data/Silver_Project_Data.xlsx')
print(df.shape)        # (2534, 14)
print(df.columns.tolist())
# ['Date', 'USD_Index', 'Gold', 'Silver', 'Gold_Silver_Ratio',
#  'Silver_Daily_Return', 'RSI', 'SMA50', 'SMA200', 'Month',
#  'Daily_Return', 'Returns', 'Anomaly', 'Prev_Silver']

df.describe()
```

---

## Disclaimer

This report is provided for **informational purposes only** and does not constitute investment advice, financial advice, or trading advice of any kind. Past performance is not indicative of future results. Precious metals markets can be highly volatile and subject to rapid price movements.

All data is believed accurate as of the report date (February 2, 2026) but should be independently verified. Readers should consult qualified financial advisors before making any investment decisions.

---

<div align="center">
  <strong>Silver Market Analysis · 2016–2026</strong><br/>
  Analyst: Nilansh Agarwal · Report Date: February 2, 2026
</div>
