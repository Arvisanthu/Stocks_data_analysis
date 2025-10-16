

## 📊 **Project Title:** Time Series Data Analysis on S&P 500 Stocks

---

### 🎯 **Project Objectives**

* To analyze the **time-series trends** of S&P 500 companies and understand their stock price movements over time.
* To calculate **daily returns** and identify trends, patterns, and correlations between major tech stocks.
* To study **moving averages** and **resampling analysis** to smooth data and uncover long-term stock performance.
* To evaluate whether stock prices and returns of major companies (Amazon, Apple, Google, Microsoft) are correlated.

---

### 🧠 **Methods**

1. **Data Collection:**

   * Historical stock data for S&P 500 companies (likely sourced via APIs such as Yahoo Finance or CSV dataset).

2. **Data Cleaning & Preparation:**

   * Checked for missing values and formatted timestamps.
   * Converted date columns to `datetime` format for time-series analysis.

3. **Exploratory Time-Series Analysis:**

   * **Trend Analysis:** Examined the change in stock price over time for each company.
   * **Moving Average:** Computed rolling averages (e.g., 10-day, 50-day, 200-day) to observe smoothed performance trends.
   * **Resampling Analysis:** Aggregated daily prices into monthly and quarterly averages to detect macro trends.
   * **Volatility Analysis:** Calculated daily returns using the formula:
     [
     \text{Daily Return} = \frac{\text{Close} - \text{Open}}{\text{Open}}
     ]

4. **Correlation Study:**

   * Analyzed the **closing price correlations** among Amazon, Apple, Google, and Microsoft.
   * Evaluated **daily return correlations** to see how similarly the stocks move.

5. **Visualization:**

   * Time series plots for closing prices and moving averages.
   * Heatmaps to represent correlations between stock returns.
   * Line charts for trend and volatility comparison.

---

### 🧾 **Dataset**

* **Source:** Historical stock prices for S&P 500 companies.
* **Likely Columns:** `Date`, `Open`, `High`, `Low`, `Close`, `Volume`, `Adj Close`.
* **Key Stocks Analyzed:** Amazon, Apple, Google (Alphabet), Microsoft.
* **Data Type:** Time-indexed numerical dataset (daily frequency).

---

### 📈 **Results**

* **Stock Trends:**
  Each stock showed a distinct trend — Apple and Microsoft exhibited steady long-term growth; Amazon displayed higher volatility; Google maintained consistent performance.

* **Moving Average Findings:**
  Longer moving averages (e.g., 50-day or 200-day) effectively captured trend reversals and major market shifts.

* **Resampling Analysis:**
  Monthly and quarterly aggregations helped visualize macro-level growth trends, smoothing out short-term fluctuations.

* **Correlation Insights:**

  * Closing prices among tech giants were **strongly correlated**, showing similar movement patterns due to sector influence.
  * Daily returns also demonstrated **moderate to high correlation**, suggesting interdependence in investor sentiment and market trends.

---

### 💡 **Insights**

* Tech stocks in the S&P 500 index are **highly interrelated**, often moving in the same direction in response to global market events.
* **Moving averages** serve as effective tools to understand both short-term momentum and long-term trends.
* **Resampling** provides better clarity on market behavior by reducing noise in high-frequency data.
* The analysis highlights that **diversification within the same tech sector** may not significantly reduce risk due to strong correlations.
* Future extensions can include **forecasting models** like ARIMA, Prophet, or LSTM to predict future stock movements.

---

