# ds_sreekanth

📊 Trader Performance & Market Sentiment Analysis
🧠 Project Overview

This project analyzes the relationship between trader performance and market sentiment using historical cryptocurrency trading data combined with the Fear-Greed Index.
The goal is to uncover how sentiment phases (Extreme Fear → Extreme Greed) influence profitability, volatility, and strategic trading outcomes.

🗂️ Dataset Information

Files Used:

trades.csv → Contains 211,224 trading records

sentiment.csv → 2,644 daily Fear-Greed Index readings

merged_dataset.csv → 35,864 trades aligned with sentiment data

Date Range: January 2023 – May 2025
Key Columns:

Date, PnL, Trade Type (BUY/SELL), Sentiment, Sentiment Score

⚙️ Data Processing & Methodology

Data Cleaning & Merging:

Standardized timestamps and merged trading and sentiment data.

Removed null and inconsistent records.

Feature Engineering:

Classified sentiment into 5 phases (Extreme Fear → Extreme Greed).

Computed key metrics: mean, median, and standard deviation of PnL.

Analysis Performed:

Performance comparison across sentiment phases.

Long vs. Short strategy analysis.

Volatility and risk-reward profiling.

Correlation between sentiment and PnL.

📈 Key Findings

Extreme Greed: Highest profits but highest volatility.

Fear: Second-best returns — profitable contrary to common belief.

Extreme Fear: Lowest profits, lowest volatility — stable but slow.

Contrarian Strategy Works: Short during Greed, Long during Fear.

📉 Visuals Included

(Placeholders — visuals generated in Jupyter Notebook)

Figure 1: Sentiment Distribution

Figure 2: PnL Distribution by Sentiment

Figure 3: BUY vs SELL Performance by Sentiment

Figure 4: Volatility vs Average PnL


🧾 Report

The full project report, “Trader_Performance_Sentiment_Report.docx”, contains:

Executive Summary

Data Overview

Exploratory Analysis

Statistical Results

Insights, Recommendations, and Limitations

💻 Tools & Technologies

Python Libraries: pandas, matplotlib, seaborn, numpy

Notebook: Jupyter Notebook

Visualization: Matplotlib/Seaborn

Documentation: Microsoft Word

🚀 How to Run

Download all files (.ipynb, .csv, .docx) into the same folder.

Open notebook_1.ipynb in Jupyter Notebook or Google Colab.

Run all cells sequentially to reproduce the analysis.

View visuals and statistical results directly in the notebook.

📚 Future Enhancements

Add time-series sentiment trend analysis.

Build a predictive model using sentiment and PnL.

Automate dashboard visualization for real-time insights.

👤 Author

Sreekanth Reddy Polu
Data Science & Machine Learning Enthusiast
📧 Email: [your email]
💼 GitHub: [your GitHub profile link]
