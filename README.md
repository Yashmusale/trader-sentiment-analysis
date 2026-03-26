
# Trader Performance vs Market Sentiment

## 📌 Objective

Analyze how market sentiment (Fear/Greed) impacts trader behavior and performance.

---

## ⚙️ Setup Instructions

1. Clone the repository
2. Install dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 📊 Methodology

* Cleaned and standardized dataset columns
* Converted timestamps and merged datasets on date
* Created metrics:

  * Daily PnL
  * Win rate
  * Trade size
  * Trade frequency
* Compared trader behavior across Fear vs Greed sentiment

---

## 🔍 Key Insights

1. Traders tend to perform better during Greed phases with higher average PnL.
2. During Fear, traders reduce position sizes and trade less frequently.
3. High trade-size traders generate higher returns but also face higher risk.

---

## 💡 Strategy Recommendations

* During Fear: Reduce trade size and avoid high-risk trades
* During Greed: Increase participation but apply strict risk management

---

## 🚀 Bonus Work

* Built a simple predictive model to classify profitable trades
* Clustered traders into behavioral segments

---



---
