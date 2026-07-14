# PrimeTrade AI - Trader Performance Analysis

## 📌 Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using the Bitcoin Fear & Greed Index and Hyperliquid historical trading data. The goal is to identify trading patterns, evaluate trader performance under different market conditions, and provide data-driven insights for smarter trading strategies.

---

## 🎯 Objectives

- Analyze trader performance under different market sentiments.
- Explore the relationship between market sentiment and trading profitability.
- Identify hidden patterns in trading behavior.
- Generate actionable trading strategy recommendations.

---

## 📂 Datasets

### 1. Historical Trader Data
Contains detailed trading information including:
- Account
- Coin
- Execution Price
- Size (USD)
- Side (BUY/SELL)
- Closed PnL
- Fee
- Timestamp

Dataset Link:
https://drive.google.com/file/d/1M0b8bMDWVoPe5GAeXcm5B3FwGl32du1_/view?usp=sharing
### 2. Bitcoin Fear & Greed Index
Contains daily market sentiment values:
- Fear
- Extreme Fear
- Neutral
- Greed
- Extreme Greed

Dataset Link:
https://drive.google.com/file/d/1G7QuCwWzEnBDn57Yahyo7BjqzSc6Sx7n/view?usp=sharing

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📊 Analysis Performed

- Data Loading and Cleaning
- Data Merging
- Exploratory Data Analysis (EDA)
- Trade Count Analysis
- Average Closed PnL Analysis
- Total Closed PnL Analysis
- Win Rate Analysis
- Buy vs Sell Analysis
- Average Trade Size Analysis
- Top Trader Analysis
- Coin Performance Analysis
- Fee vs Closed PnL Analysis
- Trade Size vs Closed PnL Analysis
- Correlation Heatmap

---

## 🔍 Key Findings

- Extreme Greed achieved the highest average Closed PnL.
- Fear generated the highest total Closed PnL.
- Extreme Greed recorded the highest win rate.
- Fear had the highest trading activity.
- HYPE was the most traded cryptocurrency.
- @107 generated the highest cumulative Closed PnL.
- @109 achieved the highest average profit per trade.
- Trade size and trading fees showed only weak relationships with profitability.

---

## ▶️ How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries using:

```bash
pip install -r requirements.txt
```

3. Download the datasets from the links above.
4. Upload the datasets when prompted.
5. Run all notebook cells from top to bottom.

---

## 📁 Repository Structure

```
PrimeTrade-AI-Trader-Performance-Analysis/
│
├── PrimeTrade_AI_Assignment.ipynb
├── README.md
├── requirements.txt
├── fear_greed_index.csv
```

---

## 👤 Author

**Ramani S**
