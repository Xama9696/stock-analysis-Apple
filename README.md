# 📊 Stock Analysis Dashboard

## 📌 Overview

This project focuses on analyzing stock market data and visualizing key financial trends using Python and Tableau.
The goal is to understand price movements, trends, and volatility over time through an interactive dashboard.

---

## ⚙️ Tech Stack

* **Python** (Pandas, NumPy)
* **Tableau Public**
* **Jupyter Notebook**

---

## 📂 Dataset

* Historical stock data (AAPL)
* Source: Nasdaq / Yahoo Finance
* Features include:

  * Date
  * Open, High, Low, Close
  * Volume

---

## 🔍 Data Processing (Python)

Performed in Jupyter Notebook:

* Cleaned and formatted stock data
* Converted date columns
* Calculated:

  * **Daily Returns**
  * **Moving Averages (7-day & 30-day)**
  * **Volatility (Rolling Standard Deviation)**

Final dataset exported as:

```
finance_dashboard.csv
```

---

## 📈 Dashboard (Tableau)

The dashboard includes:

### 1. Price Trend

* Visualizes stock closing price over time

### 2. Moving Average

* Shows short-term (MA7) and long-term (MA30) trends
* Helps identify trend direction

### 3. Volatility

* Displays fluctuations in stock returns
* Useful for understanding risk

---

## 🎯 Key Insights

* Stock shows overall upward movement across the period
* Short-term fluctuations captured via moving averages
* Volatility highlights periods of higher market uncertainty

---

## 🚀 How to Run

### Step 1: Run Notebook

* Open `stock_analysis.ipynb`
* Execute all cells

### Step 2: Open Tableau

* Load `finance_dashboard.csv`
* Recreate or view dashboard

---

## 📁 Project Structure

```
stock-analysis-dashboard/
│
├── data/
│   └── HistoricalData.csv
│
├── notebooks/
│   └── stock_analysis.ipynb
│
├── output/
│   └── finance_dashboard.csv
│
├── dashboard/
│   └── tableau_dashboard.twbx
│
└── README.md
```

---

## 💡 Future Improvements

* Add KPI cards (avg return, max price)
* Include multiple stocks comparison
* Add predictive modeling for price trends

---

## 👤 Author

Mohammad Zaman Asif
