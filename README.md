# 📊 Energy Commodity Price Analysis

## 📌 Project Overview

This project analyzes historical price data of major energy commodities including **Crude Oil, Brent Oil, Natural Gas, and Heating Oil**. The objective is to understand price trends, volatility, correlations, and seasonal patterns using time-series data analysis.

---

## 🎯 Objectives

* Analyze price trends over time
* Compare volatility across commodities
* Identify correlations between energy markets
* Detect seasonal patterns

---

## 📁 Dataset Description

The dataset consists of multiple CSV files containing historical data for:

* Crude Oil
* Brent Oil
* Natural Gas
* Heating Oil

These datasets were merged into a single dataset (`merged.csv`) for analysis.

### Key Features:

* Date
* Open, High, Low, Close prices
* Volume

---

## 🛠️ Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🔧 Data Preprocessing

* Converted `Date` column to datetime format
* Handled missing values using forward fill
* Removed duplicate records
* Fixed column inconsistencies
* Created new features:

  * Year and Month
  * Returns (percentage change)
  * Moving averages
  * Volatility

---

## 📊 Exploratory Data Analysis (EDA)

### 📈 Trend Analysis

* Visualized price movements of all commodities over time
* Identified overall growth trends and fluctuations

### 🔗 Correlation Analysis

* Analyzed relationships between different commodities
* Used heatmaps to understand correlation strength

### 📅 Seasonal Analysis

* Examined monthly average prices
* Identified seasonal variations

### 📉 Volatility Analysis

* Compared price fluctuations using rolling standard deviation

---

## 📊 Key Insights

* Crude Oil and Brent Oil exhibit strong positive correlation
* Natural Gas shows higher volatility compared to other commodities
* Heating Oil demonstrates seasonal price patterns
* Moving averages indicate relatively stable long-term trends in crude oil

---

## 💼 Business Insights / Interpretation

* Diversification across commodities can reduce investment risk
* Seasonal trends can help in planning trading strategies
* Natural Gas offers higher risk-reward opportunities
* Crude Oil is relatively stable for long-term analysis

---

## 📁 Project Structure

```
Energy-Analysis/
│── data/
│── End-to-End.ipynb
│── merged.csv
│── README.md
```

---

## 🚀 Conclusion

This project demonstrates how time-series data analysis can be used to extract meaningful insights from energy market data and understand relationships between different commodities.

---

## 📌 Future Improvements

* Build an interactive dashboard (Power BI/Tableau)
* Apply forecasting models (ARIMA, LSTM)
* Include real-time data integration

---
