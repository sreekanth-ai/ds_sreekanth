# ds_sreekanth

## 📊 Trader Performance & Market Sentiment Analysis
## 🧠 Project Overview

This project analyzes the relationship between trader performance and market sentiment using historical cryptocurrency trading data combined with the Fear-Greed Index.
The goal is to uncover how sentiment phases (Extreme Fear → Extreme Greed) influence profitability, volatility, and strategic trading outcomes.

## 🗂️ Dataset Information

**Files included**
- `trades.csv` — 211,224 trading records  
- `sentiment.csv` — 2,644 daily Fear‑Greed Index readings  
- `merged_dataset.csv` — 35,864 trades aligned with sentiment data  

**Date Range:** January 2023 – May 2025  
**Key Columns:** `Date`, `PnL`, `Trade_Type` (BUY/SELL), `Sentiment_Class`, `Sentiment_Score`

## ⚙️ Data Processing & Methodology

1. **Data cleaning & merging**
   - Standardized timestamps, removed invalid records, and performed an inner join on date.
2. **Feature engineering**
   - Binned sentiment scores into categories: Extreme Fear, Fear, Neutral, Greed, Extreme Greed.
   - Computed summary statistics (mean, median, std) for PnL.
3. **Analysis**
   - Aggregations by sentiment class and trade direction.
   - Volatility (std) and risk‑reward profiling.
   - Correlation analysis between sentiment score and PnL.


## 📈 Key Findings

- **Extreme Greed:** Highest average returns ($205.82) and highest volatility ($1,861.56). High risk, high reward.  
- **Fear:** Second-highest returns ($128.29) with substantial volatility — long positions during Fear were surprisingly profitable.  
- **Extreme Fear:** Lowest returns ($1.89) and lowest volatility ($76.73) — capital preservation phase.  
- **Strategy insight:** Contrarian strategies work well — short during Extreme Greed, long during Fear.


## 📉 Visuals Included

Include these figures in the notebook and insert into the report:
- **Figure 1:** Distribution of Sentiment Classes *(Placeholder)*  
- **Figure 2:** PnL Distribution Histogram *(Placeholder)*  
- **Figure 3:** PnL by Sentiment Boxplot *(Placeholder)*  
- **Figure 4:** BUY vs SELL Performance per Sentiment *(Placeholder)*  
- **Figure 5:** Volatility vs Mean PnL Scatter *(Placeholder)*  
- **Figure 6:** Sentiment vs PnL Correlation Heatmap *(Placeholder)*


## 🧾 Report

### The full project report, “Trader_Performance_Sentiment_Report.docx”, contains:

- Executive Summary

- Data Overview

- Exploratory Analysis

- Statistical Results

- Insights, Recommendations, and Limitations

## 💻 Tools & Technologies

- Python Libraries: pandas, matplotlib, seaborn, numpy

- Notebook: Jupyter Notebook

- Visualization: Matplotlib/Seaborn

- Documentation: Microsoft Word

## 🚀 How to Run

- Download all files (.ipynb, .csv, .docx) into the same folder.

- Open notebook_1.ipynb in Jupyter Notebook or Google Colab.

- Run all cells sequentially to reproduce the analysis.

- View visuals and statistical results directly in the notebook.

## 📚 Future Enhancements

- Add time-series sentiment trend analysis.

- Build a predictive model using sentiment and PnL.

- Automate dashboard visualization for real-time insights.

👤 Author

Sreekanth Reddy Polu
Data Science & Machine Learning Enthusiast
<p>📩 Email: <a href="mailto:polusreekanthreddys@gmail.com">polusreekanthreddys@gmail.com</a></p>
