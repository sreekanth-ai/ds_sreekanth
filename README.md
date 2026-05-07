# 📊 Trader Performance & Market Sentiment Analysis

## 📌 Domain
Cryptocurrency Trading | Data Analytics | Market Sentiment Analysis

## 🧠 Project Overview

This project analyzes the relationship between cryptocurrency trader performance and overall market sentiment using historical trading data combined with the Fear & Greed Index.

The objective is to understand how different market sentiment phases influence:

* Profitability
* Trading risk
* Volatility
* BUY/SELL strategy performance

The project uncovers behavioral trading patterns and provides actionable insights for traders, analysts, and portfolio managers.

---

## 🎯 Project Objectives

* Analyze trader profitability across market sentiment phases
* Compare BUY vs SELL performance
* Measure volatility under different sentiment conditions
* Identify profitable contrarian trading opportunities
* Explore the relationship between sentiment scores and PnL

---

## 🗂️ Dataset Information

### 📁 Files Used

| File Name | Description |
|---|---|
| `trades.csv` | Historical cryptocurrency trading records |
| `sentiment.csv` | Fear & Greed Index daily readings |
| `merged_dataset.csv` | Final merged dataset for analysis |

### 📅 Date Range

January 2023 – May 2025

### 📌 Key Features

* Date
* PnL (Profit & Loss)
* Trade Type (BUY/SELL)
* Sentiment Score
* Sentiment Class

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔄 Data Processing Pipeline

1. Cleaned and standardized trading data
2. Processed sentiment dataset
3. Merged datasets using date alignment
4. Categorized sentiment into:

   * Extreme Fear
   * Fear
   * Neutral
   * Greed
   * Extreme Greed

5. Performed statistical and visual analysis

---

## 📈 Key Insights

### 🚀 Extreme Greed

* Highest average returns
* Highest market volatility
* High-risk, high-reward environment

### 📉 Fear

* Surprisingly profitable for long positions
* Strong contrarian trading opportunities

### 🛡️ Extreme Fear

* Lowest volatility
* Lowest profitability
* Suitable for capital preservation

### 💡 Strategy Insight

Contrarian strategies performed better:

* Short during Extreme Greed
* Long during Fear

---

## 📊 Visualizations

The project includes:

* Sentiment distribution analysis
* PnL distribution histogram
* PnL by sentiment boxplots
* BUY vs SELL comparison charts
* Volatility vs PnL analysis
* Correlation heatmap

---

## 💼 Business Impact

This analysis helps:

* Traders optimize strategies using sentiment
* Portfolio managers improve risk allocation
* Analysts understand market psychology
* Risk teams monitor volatility patterns

---

## 📁 Project Structure

```text
├── notebook_1.ipynb
├── trades.csv
├── sentiment.csv
├── merged_dataset.csv
├── ds_report.pdf
└── README.md
```

---

## ▶️ How to Run

1. Clone this repository

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run `notebook_1.ipynb`

---

## 📌 Future Enhancements

* Time-series sentiment trend analysis
* Predictive machine learning model
* Interactive dashboard development
* Real-time sentiment integration

---

## 👨‍💻 Author

### Sreekanth Reddy Polu

📧 Email: polusreekanthreddys@gmail.com
