# 📊 Full-Scale Stock Analytics with PySpark and Pandas

This project demonstrates a scalable, reproducible pipeline for analyzing historical stock data using PySpark and Pandas. It is designed for teaching time-series analysis, financial metrics, and data visualization in academic and professional settings.

---

## 🧠 Project Objectives

- Compute key financial indicators: daily return, volatility, moving averages, cumulative return
- Detect volume anomalies and price extremes
- Visualize trends using line, bar, and scatter plots
- Teach reproducible analytics workflows using PySpark and Pandas

---

## 📂 Dataset

- **File**: `a.us.txt`
- **Fields**: `Date`, `Open`, `High`, `Low`, `Close`, `Volume`
- **Frequency**: Daily
- **Format**: CSV with headers

---

## ⚙️ Technologies Used

| Tool        | Purpose                                  |
|-------------|-------------------------------------------|
| PySpark     | Scalable data processing and window functions |
| Pandas      | Data conversion and manipulation          |
| Matplotlib  | Line, bar, and scatter plots              |
| Seaborn     | Distribution plots and styling            |
| Jupyter     | Interactive development and teaching      |

---

## 📈 Analytics Performed

- **Daily Return**: Percentage change in closing price
- **Volatility**: 21-day rolling standard deviation
- **Moving Averages**: MA20 and MA50
- **Cumulative Return**: Log-compounded growth
- **Volume Analysis**: Top 10 spikes and scatter correlation
- **Monthly Trends**: Average close per calendar month

---

## 📊 Visualizations

- Line plots for trends and cumulative growth
- Bar plots for volume spikes and monthly averages
- Scatter plots for return vs volatility and volume vs price

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stock-analytics.git
   cd stock-analytics
