# Trader Performance vs Market Sentiment Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using the Bitcoin Fear & Greed Index and Hyperliquid historical trading data

The main goal of this project is to understand how different market sentiment categories, such as Fear, Greed, Extreme Fear, Extreme Greed, and Neutral, affect trader performance and trading behavior

---

## Project Objectives

The objectives of this project are :- 

- Clean and prepare both datasets
- Merge the datasets using the Date column
- Analyze trader performance under different market sentiments
- Compare important trading metrics across market sentiment categories
- Find useful insights and provide recommendations based on the analysis

---

## Datasets Used

### 1. Bitcoin Fear & Greed Index

This dataset contains daily Bitcoin market sentiment

Columns used:
- Date
- Classification (Fear, Greed, Extreme Fear, Extreme Greed, Neutral)
- Value

### 2. Hyperliquid Historical Trading Data

This dataset contains historical trading records.

Important columns used:
- Account
- Coin
- Closed PnL
- Size USD
- Side
- Timestamp IST

---

## Tools and Libraries

The project was completed using:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

The project was completed in the following steps:

1. Import required libraries
2. Load both datasets
3. Check missing values and duplicate records
4. Convert date columns into datetime format
5. Merge the datasets using the Date column
6. Create new features such as the Win column
7. Calculate:
   - Daily PnL
   - Win Rate
   - Average Trade Size
   - Number of Trades
   - Long vs Short Ratio
8. Compare trader performance across market sentiment categories
9. Create charts for better visualization
10. Segment traders based on their trading activity
11. Write insights and recommendations

---

## Visualizations

The following charts were created:

- Average PnL by Market Sentiment
- Win Rate by Market Sentiment
- Average Trade Size by Market Sentiment
- Total Trades by Market Sentiment
- Long vs Short Ratio
- Closed PnL Distribution (Box Plot)

---

## Key Findings

Some important findings from this analysis are:

- Extreme Greed recorded the highest Average PnL and Win Rate
- Fear periods had the highest trading activity
- The average trade size was highest during Fear
- Trading performance changed across different market sentiment categories
- Market sentiment influenced both trader activity and profitability

---

## Recommendations

Based on the analysis:

- Traders should consider market sentiment before making trading decisions
- Proper risk management is important, especially during Fear periods
- Market sentiment should be used together with technical analysis instead of relying on it alone

---

## Project Structure

```
Trader-Performance-vs-Market-Sentiment/
│
├── data/
│   ├── historical_data.csv
│   └── fear_greed.csv
│
├── notebook/
│   └── Trader_Performance_vs_Market_Sentiment.ipynb
│
├── charts/
│
├── README.md
│
└── report.pdf
```

---

## How to Run the Project

1. Download the project files
2. Open the Jupyter Notebook
3. Install the required libraries
4. Run all notebook cells in order
5. View the analysis, charts, insights, and recommendations

---

## Conclusion

This project explored the relationship between Bitcoin market sentiment and trader performance. The analysis showed that trading performance changed across different market conditions. The findings suggest that market sentiment can help traders understand market behavior better and support informed trading decisions when combined with proper risk managementS