📈 Stock Data Analysis: Tesla & GameStop (Historical Price + Revenue)
This project focuses on analyzing and visualizing historical stock prices and quarterly revenue data for two popular stocks:
Tesla (TSLA)
GameStop (GME)
The goal is to collect stock market data, extract revenue data, clean it properly, and finally generate meaningful visualizations.

🚀 Project Overview
In this notebook, we perform the following tasks:
✅ Extract historical stock price data using yfinance
✅ Extract quarterly revenue data using web scraping (BeautifulSoup)
✅ Clean and format datasets (reset index, convert date columns, remove missing values)
✅ Visualize stock price trends using a custom graph function

🧰 Tools & Libraries Used:
Python
Pandas
yfinance
BeautifulSoup4
requests
matplotlib

📌 Data Preview
🔹 Tesla Stock Data (First 5 Rows)
Stock dataset includes:
Date, Open, High, Low, Close, Volume, Dividends, Stock Splits

Example:
Date	Open	High	Low	Close	Volume
2010-06-29	1.266667	1.666667	1.169333	1.592667	281494500
🔹 Tesla Revenue Data (Last Records)

Revenue dataset contains:Date, Revenue
Example:
Date	Revenue
2010-09-30	31
2010-06-30	28
2010-03-31	21
🔹 GameStop Stock Data (First 5 Rows)

Example:
Date	Open	High	Low	Close	Volume
2002-02-13	1.620129	1.693350	1.603296	1.691667	76216000
🔹 GameStop Revenue Data (Last Records)
Example:
Date	Revenue
2006-01-31	1667
2005-10-31	534
2005-07-31	416
📊 Visualizations:A custom function make_graph() is used to plot the historical share price trend of each stock.
✅ Tesla - Historical Share Price
Tesla shows major growth over time with high volatility in later years.

✅ GameStop - Historical Share Price
GameStop shows relatively stable performance early, followed by a huge spike in later years (meme stock effect).

🧠 Key Learnings
How to collect stock market data using yfinance
How to scrape and clean revenue tables using BeautifulSoup
Proper dataset formatting (reset_index, sorting, cleaning revenue values)
Plotting graphs for data storytelling

▶️ How to Run
Clone the repository: git clone https://github.com/riturajm62-cloud/Analyzing-Historical-Stock

Install dependencies: pip install pandas yfinance beautifulsoup4 requests matplotlib

Run the notebook in Jupyter:jupyter notebook

📌 Output Generated
✅ DataFrames for:
Tesla stock data
Tesla revenue data
GameStop stock data
GameStop revenue data

✅ Graphs for:
Tesla historical share price
GameStop historical share price

👨‍💻 Author:Ritu Raj
