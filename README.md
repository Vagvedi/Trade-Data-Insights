# Trade-Data-Insights


## 📊 Bitcoin Trader Sentiment Analysis

### 🚀 Overview

This project explores the relationship between **market sentiment** (Fear/Greed Index) and **trader performance** using historical trading data from **Hyperliquid**.

> **Goal:**
> Uncover insights and patterns that can help drive smarter trading strategies based on psychological market behavior.



### 📁 Datasets Used

1. **📈 Trader Data** (Hyperliquid)

   * Columns: `Account`, `Coin`, `Execution Price`, `Size Tokens`, `Size USD`, `Side`, `Timestamp`, `Closed PnL`, `Start Position`, `Direction`, etc.

2. **📉 Bitcoin Market Sentiment**

   * Columns: `Date`, `Classification` (`Fear`, `Greed`, `Extreme Greed`, `Neutral`)

 🔍 Key Insights

* 💸 Traders tend to take **larger positions** during `Greed`, but **PnL is more volatile**.
* 😨 `Fear` phases show **more consistent profitability** for cautious traders.
* 🎯 Distribution plots reveal **outliers in PnL** during `Extreme Greed` events.
* 📅 All trades from the dataset initially had timestamp issues (1970) — cleaned using `Timestamp IST`.



### 📊 Visualizations

* ✅ **Boxplots** showing PnL spread per sentiment
* ✅ **Violin + Strip combo** for rich distribution visualization
* ✅ **KDE plots** to show density of trade sizes and leverage
* ✅ **Bar charts** comparing average PnL & trade size
* ✅ **Line plots** for temporal sentiment trends

  
 🛠 Tech Stack

* 🐍 Python (Pandas, NumPy)
* 📊 Seaborn + Matplotlib
* ☁️ Google Colab
* 📁 GitHub


💼 Ideal For

* Hiring managers looking for data scientists who can:

  * Clean & wrangle complex datasets
  * Derive **actionable insights**
  * Present with **clarity + visualization**

📬 How to Reach Me

📧 Email: vagvedikinikar@gmail.com
🔗 GitHub: https://github.com/Vagvedi
💼 LinkedIn: https://www.linkedin.com/in/vagvedikinikar/

