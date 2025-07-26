# Quant Finance – 45 Day Sprint

## Overview
This repository documents my **45-day journey to mastering quant finance and financial data analysis** through hands-on projects.  
Each day focuses on a specific concept or technique — from stock price visualization and portfolio optimization to options pricing, risk management, and backtesting strategies.

---

## Goals of This Sprint
- Build a **solid foundation** in quantitative finance, risk, and trading analytics.
- **Learn by doing:** Implement concepts in Python (no boring theory!).
- Create a **GitHub portfolio** showcasing daily progress.
- Explore **real-world applications** — buy-side analytics, portfolio management, and algo-trading.

---

## Tech Stack
- **Languages:** Python  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `yfinance`, `scipy`, `scikit-learn`, `statsmodels`
- **Tools:** Jupyter Notebook, VS Code, Git/GitHub

---

## Project Structure
```
quant-finance-45-day-sprint/
│
├── notebooks/
│   ├── Day01_Download_Plot_Stock_Prices.ipynb
│   ├── Day02_Daily_Returns_Volatility.ipynb
│   └── ...
│
├── scripts/           # Reusable Python scripts (data fetching, risk metrics)
├── data/              # Raw & processed data
├── images/            # Plots and charts
├── requirements.txt   # Dependencies
└── README.md          # Project overview
```

---

## Progress
| Day | Project | Status |
|-----|---------|--------|
| 1   | Download & Plot Stock Prices | ✅ Done |
| 2   | Daily, Monthly, Annual Returns | ⏳ In Progress |
| 3   | Portfolio Return & Volatility | ⏳ |
| ... | ... | ... |

---

## Sample Outputs
![Sample Plot](images/efficient_frontier.png)  
_(Example: Efficient Frontier Plot from Day 26)_

---

## How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/quant-finance-45-day-sprint.git
   cd quant-finance-45-day-sprint
   ```
2. Create a virtual environment:
   ```bash
   python -m venv .venv
   .\.venv\Scripts\activate  # Windows
   source .venv/bin/activate  # Mac/Linux
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open notebooks in VS Code or Jupyter Lab.

---

## Key Learnings
- **Day 1:** Downloaded historical data for AAPL using `yfinance`, explored price trends, moving averages, and daily returns.
- **Day 2:** Calculated log vs simple returns and plotted rolling volatility.
- **Day 3+:** Started building portfolio risk models.

---

## Next Steps
- Add **streamlit dashboards** for interactive risk analysis.
- Implement **machine learning models** for price prediction and factor analysis.
- Build **backtesting framework** for trading strategies.

---

## Connect
If you're interested in quant finance or have feedback, feel free to reach out or open an issue.  
