# Milestone II Overview

This milestone involves analyzing New York Times (NYT) headlines and historical stock market data to explore potential relationships between news events and stock market performance and conducting EDA to proactively find and problem-solve potential data issues. This project milestone is divided into three Jupyter notebooks:

## 1. `nyt_kaggle_analysis.ipynb`

**Objective**: Analyze the existing NYT Headline dataset from Kaggle.

In this notebook, we:
- Utilize the dataset from [Kaggle](https://www.kaggle.com/datasets/johnbandy/new-york-times-headlines), which contains NYT headlines collected from January 1, 1990, to the end of 2020.
- Conduct exploratory data analysis (EDA) to check for data missingness, imbalance and scaling.

## 2. `nyt_api.ipynb`

**Objective**: Supplement our existing NYT headline dataset by fetching more recent headlines (2020-2024).

In this notebook, we:
- Use the New York Times Article Search API to scrape headlines from 2020 to the present.
- Match these additional headlines to the existing dataset, which currently includes headlines from 1980 to 2020.
  
By combining the Kaggle dataset and API-scraped data, we create a comprehensive dataset spanning from 1980 to 2024.

## 3. `stock_market_data.ipynb`

**Objective**: Retrieve and explore historical stock market data to analyze market behavior over time.

In this notebook, we:
- Use Python's `yfinance` library to pull historical stock data for the S&P 500, an index tracking the performance of 500 large companies and representing the broader market.
- Conduct exploratory data analysis (EDA) to check for data missingness, imbalance and scaling.

## Data Sources
- [New York Times Article Search API](https://developer.nytimes.com/docs/articlesearch-product/1/overview)
- [Kaggle NYT Headline Dataset](https://www.kaggle.com/datasets/johnbandy/new-york-times-headlines)
- [Yahoo Finance API through `yfinance` library](https://pypi.org/project/yfinance/)
