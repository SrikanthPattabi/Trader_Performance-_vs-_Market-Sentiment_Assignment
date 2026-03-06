# Trader_Performance-_vs-_Market-Sentiment_Assignment
This is the assignment for data Analyst Role
# Trader Behavior vs Market Sentiment Analysis

This project analyzes how trader profitability and behavior change under different market sentiment conditions such as Fear and Greed using Python data analysis and visualization.

## Project Overview

This project analyzes how trader behavior and profitability change under different market sentiment conditions such as Fear, Greed, and Neutral.

The goal of this analysis is to understand whether market sentiment influences trader performance, trading style, and leverage usage.

Using data analysis and visualization, this project explores patterns between sentiment indicators and trading outcomes.

---
##

trader-sentiment-analysis
│
├── data
│   ├── sentiment.csv
│   └── trader_data.csv
│
├── notebook
│   └── analysis.ipynb
│
├── charts
│
├── README.md
## Dataset

The analysis uses two main datasets:

1. **trader-sentiment-analysis data set**

   * Account
   * Trade side (Long / Short)
   * Closed PnL
   * Leverage
   * Trade time

2. **trader-sentiment-analysis data set**

   * Date
   * Sentiment classification

     * Extreme Fear
     * Fear
     * Neutral
     * Greed
     * Extreme Greed

Both datasets were merged based on date to analyze how sentiment affects trading performance.

---

## Tools & Technologies

The following tools were used in this project:

* Python
* Pandas – Data cleaning and transformation
* NumPy – Numerical operations
* Matplotlib / Seaborn – Data visualization
* Jupyter Notebook – Analysis environment

---

## Analysis Performed

### 1. PnL vs Sentiment

This analysis calculates total trader profit or loss for each sentiment category.

| Sentiment     | Total PnL |
| ------------- | --------- |
| Extreme Fear  | 34.53     |
| Fear          | 54.29     |
| Neutral       | 34.30     |
| Greed         | 42.74     |
| Extreme Greed | 67.89     |

**Insight:**
Traders generated the highest profit during **Extreme Greed** periods, suggesting stronger bullish market momentum.

---

### 2. Trade Frequency vs Sentiment

This analysis measures how often traders execute trades under different sentiment conditions.

**Insight:**
Trading activity tends to increase during **Fear and Greed phases**, indicating traders react strongly to emotional market conditions.

---

### 3. Leverage Distribution

This analysis explores how leverage is used across different trades.

**Insight:**
Higher leverage appears more frequently during **Greed periods**, which may indicate increased risk-taking behavior.

---

### 4. Long vs Short Trade Ratio

This analysis compares the number of long and short trades under different market sentiments.

**Insight:**
During **Greed**, traders tend to take more **Long positions**, while **Fear periods** show more balanced trading behavior.

---

### 5. Trader Performance Segmentation

Traders were grouped into four performance segments based on total PnL:

* Low Performers
* Medium Performers
* High Performers
* Top Performers

This segmentation helps identify which trader groups perform better under different sentiment conditions.

---

## Strategy Ideas (Actionable Insights)

**Strategy 1 — Sentiment Based Positioning**

When market sentiment is **Extreme Greed**, traders may benefit from maintaining **long positions**, as the market tends to show stronger bullish momentum.

**Strategy 2 — Risk Control During Fear**

During **Fear or Extreme Fear**, traders should consider **reducing leverage and trade size** to manage downside risk.

---


## Conclusion

This project demonstrates how market sentiment can influence trading behavior and profitability.

By combining sentiment data with trading performance, traders and analysts can better understand market psychology and potentially improve trading strategies.

---

## How to Run This Project

1. Clone the repository
git clone https://github.com/yourusername/trader-sentiment-analysis.git

2. Install required libraries
pip install -r requirements.txt

3. Open the Jupyter Notebook
jupyter notebook

4. Run the analysis notebook
notebooks/trader_sentiment_analysis.ipynb

## Author

Srikanth Pattabi
Data Analyst Enthusiast
