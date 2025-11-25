# ds_MaheshJadhav
Data Science assignment: Analysis of trader behavior vs market sentiment (Fear &amp; Greed Index + Historical Trader Data).

https://colab.research.google.com/drive/1WZOfihbl7HWsbjbSr682bPx0O6lsX9ql?usp=sharing


Data Science Assignment – Trader Behavior vs Market Sentiment

This project explores how trader behavior changes with overall market sentiment. I used two datasets:

Fear & Greed Index (market sentiment)

Historical Trader Data (trade actions and PnL)

The goal was to see whether traders behave differently during fear and greed periods.

Tasks Completed
1. Data Cleaning

Converted timestamps into proper datetime format

Removed missing or invalid rows

Converted numeric columns

Standardized sentiment values:

Fear = 0

Greed = 1

2. Sentiment Processing

The sentiment dataset was cleaned and merged with the trader dataset using the date column.
This allowed trade actions to be compared across different sentiment periods.

3. Analysis Performed
A. PnL vs Sentiment

Calculated average profitability on fear vs greed days.

B. Trading Volume vs Sentiment

Used Size USD to understand how much capital traders committed.

C. Risk Exposure vs Sentiment

Since the dataset did not include leverage, trade size was used as a risk indicator.

Visualizations

All charts are saved in the outputs/ folder:

pnl_vs_sentiment.png

volume_vs_sentiment.png

risk_vs_sentiment.png

These help visualize how trader behavior shifts with sentiment.

How to Run the Notebook

Open Google Colab

Upload the two CSV files into csv_files/

Run all cells in notebook_1.ipynb

The charts will be generated and saved inside outputs/

Review insights in ds_report.pdf

Tools Used

Python

Pandas

Matplotlib

Google Colab
