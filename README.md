# Trader Performance vs Market Sentiment Analysis

## Overview

This project analyzes how market sentiment (Fear vs Greed) influences trader behavior and trading performance on the Hyperliquid platform. By combining trader transaction data with the Bitcoin Fear & Greed Index, the analysis explores whether traders behave differently during Fear and Greed market conditions.

The goal is to identify patterns in trader profitability, trade frequency, and risk-taking behavior under different market sentiments.

---

## Objective

* Analyze the relationship between **market sentiment** and **trader performance**
* Understand how **trader behavior changes during Fear vs Greed periods**
* Generate **actionable insights and strategy recommendations** based on data analysis

---

## Datasets

Two datasets were used in this project:

1. **fear_greed_index.csv**
   Contains the Bitcoin Fear & Greed Index values representing daily market sentiment.

2. **historical_data.zip**
   Contains historical trader transaction data from the Hyperliquid platform.
   The dataset is provided as a compressed file due to GitHub file size limitations.

---

## Project Workflow

The analysis was performed in the following steps:

1. **Data Loading**

   * Import trader transaction data
   * Import Fear & Greed Index data

2. **Data Cleaning**

   * Handle missing values
   * Convert timestamps to date format
   * Prepare datasets for merging

3. **Dataset Merging**

   * Align trading data with sentiment data based on date

4. **Feature Engineering**

   * Daily trader PnL
   * Trade frequency
   * Position size
   * Sentiment classification

5. **Exploratory Data Analysis**

   * Profitability analysis
   * Trade behavior patterns
   * Risk exposure during different sentiment periods

6. **Visualization**

   * PnL vs Market Sentiment
   * Trade Frequency vs Sentiment
   * Position Size vs Sentiment

---

## Key Insights

**Insight 1**
Traders tend to generate higher average profits during **Greed market conditions**, indicating increased market participation and stronger momentum.

**Insight 2**
Trade frequency increases during **Greed periods**, suggesting that traders become more active when market sentiment is positive.

**Insight 3**
During **Fear periods**, larger position sizes often lead to higher losses, indicating higher risk exposure during uncertain market conditions.

---

## Strategy Recommendations

* Traders should **reduce leverage during Fear markets** to minimize potential losses.
* Moderate trade activity during Greed periods can help capture profitable opportunities.
* Market sentiment indicators like the **Fear & Greed Index** can be used as a signal for adjusting trading strategies.

---

## Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Repository Structure

```
trader-sentiment-analysis
│
├── Trader_Performance_vs_Market_Sentiment_Analysis.ipynb
├── README.md
│
└── data
     ├── fear_greed_index.csv
     └── historical_data.zip
```

---

## How to Run the Project

1. Clone the repository
2. Install required Python libraries
3. Open the Jupyter Notebook
4. Run all cells to reproduce the analysis and visualizations

---

## Author

Project submitted as part of the **Data Science / Analytics Intern – Round 0 Assignment**.
