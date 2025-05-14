# Pahalgam Attack Market Impact

### 📊 A Study on Nifty, VIX, and News Sentiment During the Operation Sindoor Timeline

This project explores the financial market response to the **April 22, 2025 Pahalgam terrorist attack** and India's reported **counter-response, Operation Sindoor**, through a combined analysis of **Nifty 50**, **India VIX**, and **news sentiment trends**. It is intended as a data-driven exploration of market behavior during sensitive socio-political periods.

---

## 📝 Project Summary

This analysis investigates how news sentiment and market volatility indicators align with market movements following a major geopolitical event. Using time series data and sentiment scores, the study tracks investor response over key dates — particularly from the incident to the reported counter-operation. The aim is to identify signals of behavioral shifts in Indian equity markets.

---

## 📁 Dataset Description

The project uses structured market data and unstructured news data covering:
- **Nifty Index (NSE)** performance (open, close, high, low, volume, turnover)
- **India VIX (Volatility Index)** indicators
- **News sentiment scores** from real-time headlines using NLP techniques
- Computed fields: Moving averages, lag variables, binary signals, sentiment trends

---

## ⏳ Timeline Note

> ⚠️ **Note**: *Operation Sindoor*, referenced here based on NDTV’s **May 7, 2025** article, is **not officially concluded** at the time of this analysis. All references are based on **publicly available media** and are used solely for **academic and analytical purposes**.

---

## 📈 Data Sources

1. **Nifty & VIX Data**  
   - Official [National Stock Exchange (NSE)](https://www.nseindia.com/) website

2. **Sentiment Analysis Data**  
   - Extracted using [NewsAPI](https://newsapi.org/) for real-time news headlines

3. **Operation Timeline Reference**  
   - ["Pahalgam Terror Attack: Operation Sindoor"](https://www.ndtv.com/india-news/pahalgam-terror-attack-operation-sindoor-pahalgam-payback-how-india-planned-operation-sindoor-in-15-days-8351791), NDTV, May 7, 2025

---

## 🛠️ Tools & Technologies Used

| Tool/Technology    | Purpose                          |
|--------------------|----------------------------------|
| **Python (pandas, NumPy)** | Data preprocessing, time series manipulation |
| **NewsAPI**         | Real-time news data extraction |
| **Tableau**         | Data visualization and dashboarding |
| **Git & GitHub**    | Version control and collaboration |
| **Jupyter Notebook**| Exploratory data analysis (EDA) |
| **Natural Language Processing (TextBlob)** | Sentiment scoring of news headlines |

---

## 🔍 Key Insights

- **India VIX surged** notably post-attack, indicating higher fear and uncertainty.
- **Nifty returns showed volatility**, with temporary drops and subsequent recovery aligned with Operation Sindoor news.
- **Sentiment scores from headlines** showed a meaningful correlation with market shifts, often with a 1-day lag.
- Visual signals and moving average crossovers helped highlight **buy/sell/hold** patterns during the event window.

---

## 📊 Tableau Files

Dashboards are available in the `/tableau-dashboard/` folder. These include:
1. Nifty vs VIX trendlines
2. Sentiment vs Market Returns
3. Signal Position Chart (Buy/Sell/Hold)
4. Multi-metric overlays (Nifty, Sentiment, VIX)
5. Comparative area charts
6. Heatmaps and reference lines to highlight impact zones

---

## 🗂️ Project Structure

```bash
pahalgam-attack-market-impact/
├── DataSet/                  # Nifty, VIX, and sentiment data
├── Python-File/              # EDA and sentiment code in Jupyter
├── tableau-Files/            # All Tableau files and screenshots
├── README.md                # Project documentation
└── LICENSE

---

## 🧾 Summary

This project analyzes the impact of the April 22, 2025 Pahalgam terrorist attack and the subsequent Operation Sindoor on Indian stock markets. Using Nifty 50, India VIX, and news sentiment data, the study explores how markets respond to geopolitical events. It applies time series analysis, sentiment scoring, and visual storytelling through Tableau, revealing patterns in volatility, market returns, and public sentiment before and after the incident. The findings highlight a clear correlation between news flow and market behavior, offering insights into investor psychology during sensitive national events.

---
