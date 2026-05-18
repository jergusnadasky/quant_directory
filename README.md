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

### Project 1: Volatility Surface Arbitrage Pipeline
* **Status:** Operational / Production 🟢
* **Deployment Link:** [Insert Live Dashboard or Application URL]
* **Source Code:** [Insert Specific Repository URL]

#### Description
An end-to-end quantitative execution pipeline designed to fetch real-time multi-strike options data, fit implied volatility surfaces using custom Deep Neural Networks (DNNs), and isolate structural mispricings across the term structure. 

#### Key Metrics & Implementation
* Employs automated data ingestion pipelines.
* Evaluates alpha generation via empirical backtesting.
* Implements protective risk thresholds to mitigate tail-risk exposure during sharp regime shifts.

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
