# Moving-Average-Crossover-Analyzer

This project automates Golden Cross (bullish) and Death Cross (bearish) signal detection across the S&P 500, using configurable moving-average crossover logic.
The system leverages Google Sheets as a live data layer, fetching continuously updated price feeds through the GOOGLEFINANCE API for near-real-time analysis with minimal latency. 


⚙️ Key Features

⚡ Live data streaming from Google Sheets enables on-demand updates without reloading large local datasets.

🧮 Vectorized computation in Pandas ensures efficient rolling-window calculations for 500 + tickers.

📊 Detects and visualizes Golden / Death Cross events with interactive Streamlit charts (▲ = bullish, ▼ = bearish).

🧭 “All Stocks” / “Crossed Stocks” toggle for dynamic filtering of recent signals.

📥 Downloadable crossover summary table for offline or back-testing use.
