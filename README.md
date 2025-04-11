📈 Stock and Revenue Analysis – Tesla & GameStop
This repository contains a Jupyter Notebook that performs a complete workflow to extract, clean, analyze, and visualize financial data for Tesla and GameStop. It focuses on comparing stock price trends and revenue performance over time using publicly available data.

🔍 Project Overview
This project demonstrates the use of Python and data science tools to:

Extract stock price data using the yfinance API

Scrape revenue data from web pages using BeautifulSoup

Clean and transform the data for analysis

Visualize stock prices and revenue trends interactively with plotly

It includes a custom function make_graph() that displays:

Stock price history (line chart)

Revenue over time (line chart)

Interactive timeline with zoom, hover info, and axis controls

This notebook is great for finance/data science beginners who want hands-on experience working with real-world data, or for anyone who wants to explore trends in high-profile companies like Tesla and GameStop.

📦 Dependencies
Install the required Python libraries using:

bash
Copy
Edit
pip install -r requirements.txt
Major Libraries Used:
pandas – for data manipulation

numpy – for numerical operations

yfinance – for fetching historical stock prices

plotly – for creating interactive charts

beautifulsoup4 & requests – for web scraping

IPython.display – to embed charts in Jupyter output

⚙️ How It Works
Stock Data: yfinance fetches Tesla & GameStop historical data.

Revenue Data: HTML tables from financial sites are parsed using BeautifulSoup.

Cleaning: The notebook removes formatting (e.g., $, ,), resets indices, and ensures date formats are consistent.

Visualization: The make_graph() function uses Plotly's subplots to generate time series graphs for stock prices and revenue.

🧪 Usage
To run the analysis:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install the dependencies.

Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
Run the notebook cells sequentially.

📷 Output Preview
You’ll generate interactive plots like:

Tesla Stock vs Revenue

GameStop Stock vs Revenue

Each plot includes tooltips, zoom/pan support, and is displayed directly within the notebook.

✨ Features
Web scraping and API usage in one project

Fully interactive graphs with zoom & tooltips

Clean code structure suitable for learning or extending

Compatible with modern Python versions and pandas updates (e.g., datetime parsing fix)

💡 Future Improvements
Include quarterly financials

Add profit/net income alongside revenue

Automate scraping from multiple tickers

Export plots as HTML or PNG files

📚 Learning Goals
This project helps reinforce skills in:

Data collection from APIs and the web

Data cleaning and transformation

Date/time manipulation in Python

Plotly subplots and layout customization

Building modular, reusable functions

📩 Contact
For questions or collaborations, feel free to open an issue or reach out!
