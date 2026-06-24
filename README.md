# MS FinTech Portfolio

A collection of quantitative finance, data engineering, and machine learning scripts demonstrating the application of programming logic to market analytics, asset pricing, and portfolio optimization.

---

## Portfolio Projects

### 1. Multi-Asset Portfolio Optimizer (`Portfolio_Optimizer.ipynb`)
* **Overview:** An algorithmic asset allocation engine that conducts a Monte Carlo simulation to construct and visualize Markowitz's Efficient Frontier.
* **Core Technology:** `Python`, `yfinance` (live market data API), `NumPy` (vectorized portfolio math), `Pandas`, `Matplotlib`.
* **Methodology:** Simulates 10,000 random weight variations across major equities (`AAPL`, `MSFT`, `GOOGL`, `AMZN`, `TSLA`). Generates historical daily log returns, calculates an annualized covariance matrix, and isolates optimal asset weights using the Sharpe Ratio objective function.

### 2. Automated Corporate Valuation Engine (`Automated_DCF_Valuation.ipynb`)
* **Overview:** A streamlined financial engineering script designed to automate multi-stage Discounted Cash Flow (DCF) equity valuations.
* **Core Technology:** `Python`, `NumPy`, `Pandas`.
* **Methodology:** Programmatically forecasts revenue compounding, maps user-defined free cash flow (FCF) margins, integrates the Gordon Growth Model for terminal value tracking, and discounts future asset cash flows back to baseline present value.

### 3. MarketPulse NLP Sentiment Tracker (`MarketPulse_NLP.ipynb`)
* **Overview:** A live data science pipeline that streams financial text metadata and maps market sentiment shifts via Natural Language Processing (NLP).
* **Core Technology:** `Python`, `BeautifulSoup4` (XML parsing), `NLTK.VADER` (Lexicon Sentiment Analytics).
* **Methodology:** Ingests live financial macro feeds from Yahoo Finance, tokenizes unstructured headlining metadata, and outputs continuous metric sentiment scores to detect real-time market shifts.
