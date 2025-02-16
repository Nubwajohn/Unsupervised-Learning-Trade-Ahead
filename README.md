# Unsupervised-Learning-Trade-Ahead
Unsupervised Learning: Trade & Ahead

## About

The objective is to analyze stock price data and financial indicators of NYSE-listed companies, categorize stocks based on their attributes, and derive insights into the characteristics of each group.

*Disclaimer: All datasets and reports do not represent any company, institution, or country, but just a dummy dataset for learning purposes.*

## Project Overview

To perform cluster analysis on NYSE-listed stocks based on financial indicators and provide insights for diversified investment strategies.

The goal of the project is to analyze stock price data and financial indicators of NYSE-listed companies, apply clustering techniques to group stocks with similar attributes, and generate insights to assist Trade&Ahead in developing diversified investment strategies for their clients.

## Data Description

- Ticker Symbol: An abbreviation used to uniquely identify publicly traded shares of a particular stock on a particular stock market.
- Company: Name of the company.
- GICS Sector: The specific economic sector assigned to a company by the Global Industry Classification Standard (GICS) that best defines its business operations.
- GICS Sub Industry: The specific sub-industry group assigned to a company by the Global Industry Classification Standard (GICS) that best defines its business operationsm
- Current Price: Current stock price in dollars.
- Price Change: Percentage change in the stock price in 13 weeks.
- Volatility: Standard deviation of the stock price over the past 13 weeks.
- ROE: A measure of financial performance calculated by dividing net income by shareholders' equity (shareholders' equity is equal to a company's assets minus its debt).
- Cash Ratio: The ratio of a company's total reserves of cash and cash equivalents to its total current liabilities.
- Net Cash Flow: The difference between a company's cash inflows and outflows (in dollars).
- Net Income: Revenues minus expenses, interest, and taxes (in dollars).
- Earnings Per Share: Company's net profit divided by the number of common shares it has outstanding (in dollars).
- Estimated Shares Outstanding: Company's stock currently held by all its shareholders.
- P/E Ratio: Ratio of the company's current stock price to the earnings per share.
- P/B Ratio: Ratio of the company's stock price per share by its book value per share (book value of a company is the net difference between that company's total assets and total liabilities).

## Tools

- Programming Language: Python.
- Data Manipulation & Analysis Libraries: Pandas, NumPy.
- Data Visualization Libraries: Matplotlib, Seaborn.
- Machine Learning Library: Scikit-Learn, sklearn.
- Data scaling: Z-score StandardScaler.
- Compute distance: Scipy spatial distance.
- Suppress scientific notations: pd.set_option.
- Filtering Warnings: warnings, ConvergenceWarning.
- Data Preprocessing & Exploratory Data Analysis (EDA) Tools:Excel, Google Colab.
- Clustering: Kmeans & silhouette scores
- Elbow curve: KElbowVisualizer, SilhouetteVisualizer
- Hierarchical clustering, Compute cophenetic correlation, and Create dendrograms: AgglomerativeClustering, dendrogram, linkage, cophenet.
