# 📈 Trading Bot – Pine Script for TradingView

## Overview
This repository contains multiple versions of a **Trading Bot** built using **Pine Script** for **TradingView**. The bot is designed for **automated trading strategies**, including trend-following, mean reversion, and custom risk management.

## Features 🚀
- 📊 **Multiple Trading Algorithms** – Different versions optimized for market conditions.
- 🔄 **Automated Buy/Sell Signals** – Uses technical indicators for trade execution.
- 🛠 **Customizable Parameters** – Users can adjust risk, stop-loss, and take-profit settings.
- 📈 **Supports Multiple Markets** – Crypto, Forex, and Stocks.
- 🎯 **Optimized for Backtesting** – Compare results across different time frames.

---

## 🔥 **FTMO Performance Results**
The bot was tested on an **FTMO Free Trial Account** with a **€20,000 account size**. 

### **📊 Key Trading Statistics**
| Metric | Result |
|--------|--------|
| **Start Date** | 24 May 2024 |
| **End Date** | 6 Jun 2024 |
| **Total Trades** | 403 |
| **Win Rate** | 87.10% |
| **Profit Factor** | 1.08 |
| **Sharpe Ratio** | 0.08 |
| **Max Daily Loss** | -2.85% (✅ Passed) |
| **Max Loss** | -2.98% (✅ Passed) |
| **Profit Target** | -0.21% (❌ Not Achieved) |

### **📅 Daily Performance**
| Date | Trades | Lots | Result (€) |
|------|--------|------|------------|
| 6 Jun | 11 | 0.19 | €12.30 |
| 5 Jun | 3 | 0.06 | €4.17 |
| 4 Jun | 9 | 0.12 | €10.80 |
| 3 Jun | 50 | 0.70 | -€44.73 |
| 31 May | 28 | 0.47 | €43.13 |
| 30 May | 97 | 1.82 | €69.85 |
| 29 May | 106 | 1.40 | -€41.84 |
| 28 May | 39 | 0.66 | -€28.52 |
| 27 May | 50 | 0.87 | €28.77 |
| 24 May | 10 | 0.17 | -€25.05 |

🔹 **Highlights:**  
✅ **High Win Rate (87.1%)** – The bot successfully predicted market direction in most trades.  
✅ **Passed FTMO Risk Limits** – Max Drawdown stayed within FTMO’s allowed limits.  
⚠️ **Profit Target Not Achieved** – Further optimizations needed for higher profitability.

---

## 📂 Files Included
| File Name | Description |
|-----------|------------|
| `TradingBot-3.1.pine` | Initial version with basic signal generation |
| `TradingBot-3.1.1.pine` | Improved entry/exit logic |
| `TradingBot-3.1.1.1.pine` | Enhancements in trend detection |
| `TradingBot-3.1.1.1+TradingRange.pine` | Added trading range feature |
| `TradingBot-3.1.1.3+TradingRange.pine` | Optimized range-based trading strategy |
| `TradingBot-3.2.pine` | Performance optimizations |
| `TradingBot-3.2.2.pine` | Additional fine-tuning |
| `TradingBot-3.3.pine` | Better risk management and efficiency |
| `TradingBot-3.3.3.pine` | Improved stop-loss strategy |
| `TradingBot-3.3.7.pine` | More flexible position sizing |
| `TradingBot-3.3.7.4.long` | Optimized for long trades only |
| `TradingBot-3.3.9.pine` | Latest update in 3.x series |
| `TradingBot-5.pine` | Major revision with new indicators |
| `TradingBot-5.2_raw.pine` | Unrefined raw version for testing |
| `TradingBot-5.2_10k.pine` | Settings optimized for high-volume trading |
| `TradingBot-5.2.2.pine` | Further refinements on 5.2 branch |
| `TradingBot-5.2.6.1.pine` | Advanced market trend integration |
| `TradingBot-5.3.pine` | Latest optimized version with dynamic indicators |

---

## How to Use 🏗
1. **Open TradingView** – [https://www.tradingview.com/](https://www.tradingview.com/)
2. **Go to Pine Editor** – Click on **"Pine Script Editor"** at the bottom.
3. **Copy & Paste the Script** – Open any `.pine` file and paste it into the editor.
4. **Click "Add to Chart"** – The trading bot will generate Buy/Sell signals.
5. **Adjust Settings** – Modify parameters to fit your trading strategy.
