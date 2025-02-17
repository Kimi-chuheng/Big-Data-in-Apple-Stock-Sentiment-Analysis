# Big Data in Apple Stock-Sentiment Analysis

## Project Duration
**September 2024 - November 2024**

## Project Overview
This project leverages **Google Proc** as a platform to analyze the impact of Apple Inc.'s news sentiment on stock price fluctuations. The study utilizes **big data techniques** to extract and analyze news sentiment and correlate it with stock price movements.

## Project Workflow
### 1. **Data Collection**
- News articles are scraped from [Apple Newsroom Archive](https://www.apple.com/newsroom/archive/) using the script located at:
  - `Big data project/Apple news scraper tool.ipynb`
- The scraped news data is saved as:
  - `Big data project/apple_news.csv`

- Apple stock price data is sourced from Kaggle:
  - [Apple Stock Data](https://www.kaggle.com/datasets/varpit94/apple-stock-data-updated-till-22jun2021/data)

### 2. **Data Processing & Sentiment Analysis**
- The project runs locally on **Anaconda** using **Jupyter Notebook**.
- Data analysis and sentiment scoring are performed using:
  - `Big data project/Tool for sentiment and analysis.ipynb`

### 3. **Statistical Analysis & Findings**
- The processed data is uploaded to **Google Proc** for large-scale analysis using statistical methods.
- Key findings:
  - Positive news sentiment correlates with **increased** average stock price changes over the following days.
  - Negative news sentiment correlates with **decreased** average stock price changes over the following days.
  - When sentiment drops below a certain threshold, the stock price decline becomes significantly steeper.

### 4. **Project Documentation**
- Detailed analysis, methodology, and results are documented in:
  - `Big data project/Project Documentation Chuheng.pdf`

## Tools & Technologies Used
- **Google Proc** (Big Data Cloud Platform)
- **Python** (Data Processing & Analysis)
- **Jupyter Notebook** (Local Execution)
- **Big Data Techniques** (Data Storage & Processing)
- **Web Scraping** (Apple News Scraper)
- **Statistical Methods** (Stock Sentiment Analysis)

## Conclusion
This project demonstrates a clear relationship between Apple Inc.'s news sentiment and its stock price fluctuations. The insights gained can be useful for investors and analysts in predicting market trends based on corporate news sentiment.

---
**Author:** Chuheng  
**Date:** November 2024


