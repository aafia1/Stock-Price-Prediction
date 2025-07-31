# 📈 TASK# 02 Stock Price Prediction (Short-Term)

### 👩‍💻 By: Aafia Azhar  
GitHub: [@aafia1](https://github.com/aafia1)

---

## 🎯 Task Objective
This project is part of my AI/ML internship at **DevelopersHub Corporation**. The goal is to predict the **next day's closing stock price** using historical data with features like `Open`, `High`, `Low`, and `Volume`.

---

## 📊 Dataset Used
- Source: [Yahoo Finance](https://finance.yahoo.com/)
- Tool: `yfinance` Python library
- Stock: Apple Inc. (`AAPL`) – Can be changed to any other stock symbol

---

## 🤖 Models Applied
- **Random Forest Regressor** (from `scikit-learn`)
- (You can also try Linear Regression or other models)

---

## 📈 Key Results & Findings
- Trained a Random Forest Regressor to predict the next day’s closing price
- Evaluation Metrics:
  - **Mean Squared Error (MSE)**: Shows average error between predicted and actual prices
  - **R² Score**: Measures prediction accuracy (closer to 1 is better)
- A visual plot was created comparing **actual vs predicted prices**, showing good alignment

---

## 🛠 How to Run
1. Clone or download this repo
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run `stock_price_prediction.ipynb` in Jupyter Notebook

---
