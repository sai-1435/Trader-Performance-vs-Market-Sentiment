# 📊 Trader Performance vs Market Sentiment Analysis

## 📌 Project Overview

This project analyzes the relationship between **Bitcoin Market Sentiment (Fear & Greed Index)** and **Hyperliquid trader performance**. The objective is to understand how market sentiment influences trader behavior, profitability, and trading activity.

This project was completed as part of the **Data Science Intern – Round 0 Assignment** for **Primetrade.ai**.

---

## 🎯 Objectives

- Analyze Bitcoin Fear & Greed Index data.
- Analyze Hyperliquid historical trading data.
- Merge both datasets based on trading date.
- Compare trader performance across different market sentiments.
- Generate actionable insights and strategy recommendations.

---

## 📂 Dataset

### 1. Bitcoin Fear & Greed Index
Contains:
- Date
- Fear & Greed Value
- Market Classification

### 2. Hyperliquid Historical Trader Data
Contains:
- Account
- Coin
- Execution Price
- Trade Size
- Side (Buy/Sell)
- Closed PnL
- Fee
- Timestamp
- Transaction Details

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git & GitHub

---

## 📁 Project Structure

```
Trader-Performance-vs-Market-Sentiment/
│
├── notebook/
│   ├── analysis.ipynb
│   ├── fear_greed_index.csv
│   └── historical_data (1).csv
│
├── charts/
│   ├── win_rate.png
│   ├── average_trade_size.png
│   ├── buy_sell_ratio.png
│   └── daily_pnl.png
│
├── README.md
└── requirements.txt
```

---

## 🔄 Project Workflow

1. Loaded both datasets.
2. Checked missing values and duplicates.
3. Converted timestamps into datetime format.
4. Merged datasets using trading date.
5. Created analytical metrics including:
   - Daily Profit & Loss (PnL)
   - Win Rate
   - Average Trade Size
   - Trade Count
   - Buy vs Sell Distribution
6. Visualized results using charts.
7. Derived business insights and strategy recommendations.

---

## 📈 Key Findings

### ✅ Win Rate by Market Sentiment

| Sentiment | Win Rate |
|-----------|----------|
| Extreme Greed | **46.49%** |
| Fear | 42.08% |
| Neutral | 39.70% |
| Greed | 38.48% |
| Extreme Fear | 37.06% |

---

### ✅ Average Trade Size (USD)

| Sentiment | Average Trade Size |
|-----------|-------------------:|
| Fear | **7816.11** |
| Greed | 5736.88 |
| Extreme Fear | 5349.73 |
| Neutral | 4782.73 |
| Extreme Greed | 3112.25 |

---

### ✅ Trade Count

| Sentiment | Trades |
|-----------|--------:|
| Fear | **61,837** |
| Greed | 50,303 |
| Extreme Greed | 39,992 |
| Neutral | 37,686 |
| Extreme Fear | 21,400 |

---

## 📊 Visualizations

The project includes:

- Win Rate by Market Sentiment
- Average Trade Size by Market Sentiment
- Buy vs Sell Distribution
- Daily Profit & Loss Trend

---

## 💡 Insights

### Insight 1
Traders achieved the highest win rate during **Extreme Greed** market conditions (46.49%).

### Insight 2
The largest average trade sizes were observed during **Fear** periods, indicating increased exposure during uncertain markets.

### Insight 3
Trading activity was highest during **Fear** and **Greed** periods, suggesting stronger market participation when sentiment was pronounced.

---

## 🚀 Strategy Recommendations

### Strategy 1
During **Extreme Greed**, traders may maintain disciplined long positions while applying proper risk management because historical win rates were comparatively higher.

### Strategy 2
During **Fear** periods, traders should avoid excessive position sizing and use controlled risk management to reduce downside exposure.

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/sai-1435/Trader-Performance-vs-Market-Sentiment.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open

```
notebook/analysis.ipynb
```

4. Run all notebook cells.

---

## 👨‍💻 Author

**Sai**

GitHub: https://github.com/sai-1435
