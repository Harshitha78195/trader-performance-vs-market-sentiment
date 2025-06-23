# trader-performance-vs-market-sentiment

This project explores how trader behavior correlates with Bitcoin market sentiment (Fear vs Greed). By analyzing real trader execution data alongside the Bitcoin Fear-Greed Index, we uncover patterns in performance, position direction, leverage, and profit/loss to guide smarter trading strategies.

---

##  Datasets

-  **Historical Trader Data:**  
  [Download from Google Drive](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)

-  **Bitcoin Fear-Greed Index:**  
  [Download from Google Drive](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)

---

##  Objective

To explore the relationship between:
- Trader **performance metrics** (`Closed PnL`, `Side`, `Execution Price`, etc.)
- Daily **market sentiment** (`Fear` or `Greed`)

And to identify:
- Patterns in trader profitability across sentiment phases
- Trends in trading behavior (long vs short) based on sentiment
- Risk appetite (e.g., leverage usage) during Fear vs Greed

---

##  Key Insights

-  Average PnL is higher/lower on Greed days than on Fear days.
-  Traders tend to prefer [e.g., long positions] during Greed days.
-  Leverage usage varies with market sentiment.
-  Sentiment-driven trading signals could improve outcomes.

_(See full insights and visualizations in the notebook)_

---

##  Notebook

- [`sentiment_trader_analysis.ipynb`](./sentiment_trader_analysis.ipynb)

Contains:
- Data loading & cleaning
- Timestamp alignment
- Merging trader and sentiment data
- Visualizations and EDA
- Actionable insights

---

##  Project Structure

```bash
.
├── sentiment_trader_analysis.ipynb           # Main notebook
├── outputs/                                  # (Optional visual exports)
├── README.md                                 # Project summary
