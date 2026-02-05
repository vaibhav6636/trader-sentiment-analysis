📌 Task Title

Trader Behavior vs Market Sentiment Analysis

📖 Task Overview

This project analyzes how trader behavior changes under different market sentiment conditions (Fear vs Greed). By combining historical trader transaction data with the Bitcoin Fear & Greed Index, we identify patterns in profitability, position sizing, and trading style.

The goal is to understand whether market psychology influences trader performance and decision-making.

🗂 Dataset Used
1️⃣ Trader Transaction Data

Contains historical trade records including:

Account ID

Execution Price

Trade Size (USD)

Side (Buy/Sell)

Position Type (Long/Short)

Closed PnL

Execution Timestamp

2️⃣ Bitcoin Market Sentiment Data

Daily market sentiment classification:

Fear

Greed

⚙️ Methodology

Cleaned and formatted timestamps

Extracted trading date from execution time

Merged trader data with daily sentiment using date

Performed exploratory data analysis (EDA)

Compared trader performance under Fear vs Greed

Segmented traders by:

Trade Size

Trading Activity

📊 Key Insights

✔ Traders take larger position sizes during Greed periods
✔ Average PnL is higher in Greed, but risk is also higher
✔ During Fear, traders trade smaller and more cautiously
✔ High-activity traders perform more consistently across sentiments
✔ Larger trades show higher profit variance

📈 Strategy Recommendations

• Reduce position size during Greed to manage risk
• Increase monitoring of large trades in volatile sentiment periods
• Encourage disciplined trading during Fear markets
• Use sentiment as a risk management indicator, not a signal alone

🖼 Output Visualizations

The repository includes charts showing:

PnL comparison: Fear vs Greed

Trade size behavior by sentiment

Long vs Short performance

Trader activity segmentation

Trade size segmentation

▶️ How to Run the Project

Install required libraries

pip install -r requirements.txt


Open the notebook

trader_sentiment_analysis.ipynb


Run all cells to reproduce the analysis and charts

🛠 Tools & Technologies

Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook

👤 Author

Vaibhav Shrikant Kore 
