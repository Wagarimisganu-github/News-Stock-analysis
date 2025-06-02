F📊 Financial Analysis Data Suite
A comprehensive Python-based data analysis project that combines descriptive and statistical analysis of financial datasets — including news headlines and historical stock prices — to uncover valuable insights using Jupyter Notebooks.
  Overview
This project focuses on two major areas of financial data analysis:

📰 Financial News Analysis
Analyze financial news headlines (raw_analyst_ratings.csv)

Explore publishing trends and perform sentiment classification

📈 Stock Market Statistical Analysis
Perform descriptive statistics and technical analysis

Use data from major tech companies: AAPL, GOOG, AMZN, META, MSFT, NVDA, and TSLA

✨ Features
🗞️ Financial News Analysis
Load and preview financial news headlines

Compute headline length stats (mean, median, min, max)

Analyze article publication trends by date and day of the week

Perform sentiment analysis using TextBlob

Visualizations include:

Sentiment distribution

Article frequency by time

Headline length histograms

📊 Stock Market Analysis
Load historical stock price data using yfinance

Preprocess and clean missing values

Compute daily stats: mean, std, min, max, quartiles

Generate advanced visualizations with Matplotlib and Plotly

Apply technical indicators using TA-Lib:

RSI, MACD, Bollinger Bands, etc.

Integrate sentiment scores for enriched insights

🧰 Dependencies
Install the required packages:

bash Copy Edit pip install pandas numpy matplotlib seaborn textblob plotly yfinance Optional (for technical indicators):

bash Copy Edit

Requires system-specific setup
Refer to the TA-Lib installation guide for your OS
pip install TA-Lib 📂 Dataset Descriptions

News Headlines Dataset Location: ../data/raw/raw_analyst_ratings.csv Columns:
Unnamed: 0: Index

headline: News title

url: Article link

publisher: Source

date: Publication datetime

stock: Ticker symbol

Stock Market Data Fetched via: yfinance Columns:
Open, High, Low, Close, Adj Close, Volume

Dividend & Split metadata (if available)

📊 Example Outputs 📌 Headline Statistics Mean Length: 73.12 characters

Max Length: 512 characters

📌 Top Publication Day March 12, 2020: 1,766 articles published

📌 Sentiment Breakdown Classified as Positive, Negative, or Neutral using polarity scores

📌 Stock Analysis Highlights Daily summaries and descriptive statistics

Charts with technical indicators (e.g., RSI, MACD)

Time series trends and stock comparisons

▶️ Usage bash Copy Edit

1. Clone the repository
git clone https://github.com/your-username/financial-analysis-suite.git cd financial-analysis-suite

2. Install dependencies
pip install -r requirements.txt

3. Launch Jupyter Lab or Notebook
jupyter lab 🧪 Customization Want to analyze different stocks or news datasets?

Change stock tickers in the loader section

Replace the news CSV with another file (same structure)

The pipeline adapts automatically to:

Generate new statistics

Perform updated sentiment analysis

Render new visualizations

🤝 Contributing Pull requests are welcome! For major changes, please open an issue first to discuss proposed modifications.

📜 License This project is licensed under the MIT License. Feel free to use, modify, and distribute with proper attribution.

📬 Contact For questions, suggestions, or collaboration inquiries:

Email: wagarimisganu12@gmail.com Or open an issue in the repository.
