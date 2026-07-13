# Crypto Market Risk Engine 📈

## 🎯 Project Objective
To engineer a dynamic, live-updating market monitoring system that automates risk assessment for high-volatility digital assets. This project demonstrates end-to-end data pipeline management—transforming raw API streaming data into actionable financial risk insights.

## 🛠 Technical Skills Demonstrated
* **ETL Pipeline:** Automated live data retrieval via CoinGecko API using **Power Query**.
* **Data Modeling:** Designed a relational structure between live price feeds and asset metadata.
* **Logical Programming:** Implemented **Nested IF/IFS** logic for real-time risk categorization.
* **Data Integrity:** Built error-handling systems using `IFERROR` and **Data Validation** to ensure system stability.

## ⚙️ How the System Works
1. **Extraction:** Power Query connects to the CoinGecko API to pull the top 100 coins by market cap.
2. **Transformation:** Data is cleaned and formatted; volatility is calculated as a percentage of 24h change.
3. **Load:** The "Risk Dashboard" uses `XLOOKUP` to allow users to toggle between coins and see live risk ratings.

## Local Deployment & Usage
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/D-Free33/Crypto-Market-Risk-Engine.git](https://github.com/D-Free33/Crypto-Market-Risk-Engine.git)
