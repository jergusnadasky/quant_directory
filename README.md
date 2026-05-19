# Quant ML Directory

A centralized repository designed to aggregate and serve as the single entry point for all quantitative finance and machine learning projects. This project acts as a high-signal landing page to streamline portfolio representation for professional networks and resumes.

## Live Production Link
🔗 The directory is deployed via GitHub Pages at: (https://jergusnadasky.github.io/quant_directory/)

---

## Architecture and System Design

The hub uses a minimalist, 3-column symmetrical grid layout built with semantic HTML5 and utility-first Tailwind CSS. 

* **Aspect Ratio Maintenance:** Each project card is structurally locked into a 4:3 aspect ratio (`aspect-[4/3]`) to ensure strict layout uniformity across all device viewports regardless of the dimensions of the underlying image asset.
* **Text Contrast Layering:** User interface text is isolated over complex backtest graphics or equity curve backgrounds using a precise linear gradient overlay (`from-black via-black/40 to-transparent`) to maximize legibility.

---

## Project Registry

This section catalogs the active, in-development, and planned strategies hosted within the directory infrastructure.

### Project 1: Pairs Trading Statistical Arbitrage Platform
* **Status:** Operational / Production 🟢
* **Deployment Link:** [Insert Live Dashboard or Application URL]
* **Source Code:** [Insert Specific Repository URL]

#### Description
An end-to-end quantitative research and backtesting platform designed to identify statistically cointegrated equity pairs and evaluate mean-reversion trading opportunities through interactive out-of-sample simulation. The system performs automated market data ingestion, Engle-Granger cointegration testing, rolling z-score signal generation, and portfolio performance analytics within a live interactive dashboard. 

#### Key Metrics & Implementation
* Employs automated market data ingestion pipelines using Yahoo Finance APIs and synchronized historical price normalization.
* Detects statistically significant trading pairs through Engle-Granger cointegration testing and hedge ratio estimation.
* Generates long/short trading signals using rolling spread z-score deviations and configurable mean-reversion thresholds.
* Evaluates alpha generation through out-of-sample backtesting against benchmark buy-and-hold performance.
* Implements configurable transaction cost modeling and stop-loss thresholds to reduce adverse exposure during volatile market regimes.
* Computes institutional-style performance analytics including:
    * CAGR
    * Sharpe Ratio
    * Sortino Ratio
    * Calmar Ratio
    * Annualized Volatility
    * Maximum Drawdown
    * Win Rate
* Features interactive Plotly visualizations for:
    * Equity curves
    * Z-score signal monitoring
    * Correlation heatmaps
    * Spread analysis
    * Trade execution logs
* Built with:
    * Python
    * Streamlit
    * pandas
    * statsmodels
    * Plotly
    * NumPy
    * SciPy
---

### Project 2: Order Book Imbalance LSTM
* **Status:** In Development (50% Compiled) 🟡
* **Deployment Link:** [Insert Deployment Link or Label as N/A]
* **Source Code:** [Insert Specific Repository URL]

#### Description
A high-frequency predictive model built to forecast near-term mid-price directionality utilizing Level 3 (L3) order book data. The core engine utilizes a deep Long Short-Term Memory (LSTM) network engineered to extract microstructural alpha from order flow imbalances.

#### Key Metrics & Implementation
* Tailored for low-latency inference.
* Features highly optimized data framing matrices built on NumPy and Pandas.
* Integrates native GPU-accelerated tensor operations via PyTorch.

---

### Project 3: [Insert Future Project Name]
* **Status:** Pipeline Initialization Pending
* **Deployment Link:** N/A
* **Source Code:** N/A

#### Description
[Provide a brief conceptual overview of your next quantitative framework, such as statistical arbitrage, macro regime classification, or reinforcement learning for execution.]

#### Key Metrics & Implementation
* 
* 
* 
