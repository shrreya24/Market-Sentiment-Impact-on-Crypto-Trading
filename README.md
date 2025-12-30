# Trader Behavior Insights: Market Sentiment Analysis

## 📌 Objective
The goal of this project is to analyze the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trading data. The analysis aims to uncover behavioral patterns that can inform smarter and more adaptive trading strategies.

## 📊 Datasets Used
- **Historical Trader Data (Hyperliquid)**: Includes trade-level information such as execution price, position size, trade direction, fees, and closed PnL.
- **Bitcoin Fear & Greed Index**: Provides daily market sentiment classifications including Fear, Extreme Fear, Greed, and Extreme Greed.

## 📥 Dataset Access

Due to GitHub file size limitations, the raw datasets are not included in this repository.

Please download the datasets from the following links and place them inside a `data/` folder:

- Historical Trader Data (Hyperliquid):  
  https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view

- Bitcoin Fear & Greed Index:  
  https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view

Ensure the following structure before running the notebook:

## 🛠 Data Processing
- Standardized and cleaned column names for consistency.
- Converted timestamps and aligned both datasets on a daily basis.
- Merged trader data with market sentiment using trade dates.
- Engineered features such as profitability indicators and risk measures.

## 📈 Analysis Performed
- Average trader PnL across different sentiment regimes.
- Win rate comparison by market sentiment.
- Position sizing and leverage behavior under varying sentiment conditions.
- Fee analysis to understand market activity levels.

## 🧠 Key Insights
- Trader profitability is highest during Greed and Extreme Greed phases.
- Win rates decline during Fear markets, though losses are more controlled.
- Traders increase position size and trading activity during bullish sentiment.
- Sentiment-aware strategies can significantly improve risk-adjusted performance.

## 🧰 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## ▶️ How to Run
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open and run `analysis.ipynb`
