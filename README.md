# 📊 Trader Performance vs Market Sentiment Analysis

## 📌 Overview
This project analyzes the relationship between **market sentiment (Fear vs Greed)** and **trader behavior & performance** on Hyperliquid.

The goal is to uncover actionable insights that can help design smarter trading strategies based on market psychology.

---
## 🎯 Objective
- Analyze how market sentiment affects trader performance
- Identify behavioral changes during Fear vs Greed periods
- Segment traders based on activity and risk patterns
- Provide actionable trading strategies

---

## 📂 Datasets Used

### 1. Bitcoin Market Sentiment Dataset
- Columns:
  - Date
  - Classification (Fear / Greed)

### 2. Historical Trader Data (Hyperliquid)
- Columns include:
  - account
  - symbol
  - execution_price
  - size
  - side
  - time
  - closedPnL
  - leverage
  - event

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn (optional)

---

## ⚙️ Workflow

### Part A — Data Preparation
- Loaded both datasets
- Checked:
  - number of rows and columns
  - missing values
  - duplicates
- Converted timestamps to daily format
- Merged datasets on date

### Feature Engineering
- Daily PnL per trader
- Win rate
- Average trade size
- Leverage distribution
- Number of trades per day
- Long/Short ratio

---

## 🔍 Analysis

### 1. Performance vs Sentiment
- Compared PnL and win rate across:
  - Fear days
  - Greed days

### 2. Behavior Changes
- Trade frequency
- Leverage usage
- Position size
- Long/Short bias

### 3. Trader Segmentation
- High vs Low leverage traders
- Frequent vs Infrequent traders
- Consistent vs Inconsistent traders

---

## 📊 Key Insights

- Traders tend to use higher leverage during Greed periods
- Fear periods show reduced trading activity but more cautious behavior
- High-frequency traders perform better during volatile (Fear) conditions
- Low-frequency traders perform better during stable (Greed) markets

---

## 🚀 Strategy Recommendations

### Strategy 1: Risk Management
- Reduce leverage during Fear periods
- Focus on capital preservation in volatile markets

### Strategy 2: Behavior-Based Trading
- High-frequency traders should trade more during volatile conditions
- Low-frequency traders should trade during stable market phases

---

## 📊 Visualizations
- PnL distribution by sentiment
- Leverage vs sentiment
- Trade frequency trends
- Trader segment comparisons

---

## 📁 Project Structure
