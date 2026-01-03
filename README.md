# Trader Behavior Analysis Under Market Sentiment Regimes

This repository contains my Data Science assignment submission for the **Web3 Trading Team** internship application.

The objective of this project is to analyze how trader behavior varies across different market sentiment regimes (Fear, Extreme Fear, Greed, Extreme Greed) using historical trading data and the Bitcoin Fear & Greed Index.

---

## 📊 Datasets Used

1. **Hyperliquid Historical Trader Dataset**
   - Trade-level data including execution price, trade size, direction, closed PnL, fees, and timestamps.

2. **Bitcoin Fear & Greed Index**
   - Daily market sentiment classification reflecting overall market psychology.

---

## 🧠 Methodology

- Converted trader timestamps (`Timestamp IST`) into datetime format.
- Extracted trade-level dates and aligned them with daily market sentiment.
- Merged trader activity with market sentiment using the trade date.
- Aggregated trader-level performance metrics such as:
  - Total PnL
  - Win rate
  - Trade count
  - Average trade size
  - Total fees
- Identified contrarian traders who performed well during Fear and Extreme Fear regimes.
- Visualized the distribution of PnL across different sentiment regimes.

---

## 📁 Repository Structure

ds_gokul_nair/
├── notebook_1.ipynb
├── csv_files/
│ └── processed_trader_sentiment_summary.csv
├── outputs/
│ └── pnl_by_sentiment.png
├── ds_report.pdf
└── README.md


---

## 📌 Note on Data Availability

The raw Hyperliquid trader dataset exceeds GitHub’s file size limits.  
All analysis was performed using the complete dataset in **Google Colab**.  
Only processed and aggregated CSV outputs are included in this repository.

---

## 🧪 Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

---

## 📄 Outputs

- `processed_trader_sentiment_summary.csv` – Aggregated trader performance metrics by sentiment
- `pnl_by_sentiment.png` – Visualization of Closed PnL distribution across sentiment regimes
- `ds_report.pdf` – Final summarized insights and conclusions

---

## 👤 Author

**Gokul Nair**  
MSc Data Science
