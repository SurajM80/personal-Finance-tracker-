# 📈 Personal Finance Tracker & Wealth Forecaster

### Project Overview
This project is a data analysis tool built to track mutual fund "Switch" transactions and forecast future wealth generation. It simulates the backend logic of a fintech application, moving data from a raw ledger (SQL) to an analytical engine (Python/Pandas) and finally to a decision-support visualization (Matplotlib).

### 🚀 The Real-World Scenario
I identified that my capital was underperforming in a **Liquid Fund** (Debt instrument). I executed an asset allocation switch to a **Flexi Cap Fund** (Equity instrument). This project validates that decision through data.

### 🛠️ Tech Stack
* **Python:** Core logic and calculation.
* **SQL (SQLite):** Transaction ledger storage and retrieval.
* **Pandas:** Data cleaning, manipulation, and profit calculation.
* **NumPy:** Vectorized financial math (Compound Interest).
* **Matplotlib:** Comparative visualization of growth trajectories.

### 📊 Key Features
1.  **Transaction Ledger:** A SQL-based system to log `BUY`, `SELL`, and `SWITCH` events.
2.  **Profit Calculator:** Automated calculation of Realized Profit vs. Unrealized Holdings.
3.  **Forecasting Engine:** A projection model comparing conservative (6.5%) vs. aggressive (12.5%) growth rates over 5 years.

### 📉 Visualization
The project generates a "Wealth Projection" graph that highlights the 'Opportunity Cost' of staying in a low-yield fund vs. switching to high-growth equity.

---
*Created by [SurajM80](https://github.com/SurajM80)*
