# Stock Price Prediction using Machine Learning

## Internship Task Overview
This task is part of my AI/ML Internship. The goal is to apply machine learning techniques to real-world financial data and predict the next day's stock closing price.

---

## Dataset Used
- **Source:** [Yahoo Finance](https://finance.yahoo.com/)
- **Ticker:** AAPL (Apple Inc.)
- **Time Range:** Last 5 years
- **Features Used:** Open, High, Low, Close, Volume

---

## Model Applied
- **Algorithm:** Random Forest Regressor
- **Why:** Good for regression tasks, handles non-linearity well, and gives feature importance.

---

## Key Results and Findings
- The model was trained on 80% of the data and tested on 20%.
- Achieved good predictive performance with low error.
- Important features for prediction: `Open`, `High`, `Low`, and `Volume`.

---

## How to Run
1. Clone the repo
2. Install requirements (optional):
   ```bash
   pip install -r requirements.txt
