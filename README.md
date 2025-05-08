**📊 Market Analysis: 15-Year Volatility & Growth of Big Tech
(2010--2024)**

**Project Overview**

This project delivers a data-driven exploration of long-term stock
performance across five major technology companies:

**Apple (AAPL), Amazon (AMZN), Google (GOOGL), Microsoft (MSFT), and
Nvidia (NVDA)**.

Spanning from **January 2010 to January 2025**, the analysis uses Python
and industry-standard data science libraries to answer critical business
questions related to capital growth, risk, and volatility. Through time
series plots, return calculations, and volatility visualizations, this
project reveals how each company behaved across a decade and a half of
market evolution.

**About the Dataset**

The dataset includes **daily historical stock price data** for each of
the five companies and contains:

- Opening and closing prices

- Daily highs and lows

- Timestamps from 2010 to 2024

This enables accurate analysis of **growth patterns**, **volatility
profiles**, and **comparative long-term performance** among Big Tech
firms.

**❓ Business Questions**

1.  **What is the total return of each company's stock between 2010 and
    2024?**

2.  **Which company had the highest average daily volatility over this
    period?**

3.  **How do long-term stock performance trends visually compare?**

4.  **What can we infer about each company's risk and growth
    potential?**

**Summary of Findings**

- **Nvidia (NVDA)** was the clear long-term outlier, growing over
  **31,000%** and showing the **highest daily volatility**, indicating a
  high-risk, high-reward profile.

- **Apple (AAPL)** and **Amazon (AMZN)** showed strong growth in the
  **3,000%** range with moderate volatility --- solid choices for
  balanced portfolios.

- **Microsoft (MSFT)** delivered stable growth (\~1,700%) with the
  **lowest volatility**, reinforcing its reputation as a consistent,
  conservative investment.

- **Google (GOOGL)** trailed in total return (\~1,100%), with modest
  volatility and more gradual appreciation.

- Nvidia's trajectory became exponential post-2016, while the others
  experienced steady but less dramatic upward trends.

**Analysis Features**

The Jupyter Notebook walks through the following analytical steps:

- Imported, cleaned, and formatted the dataset using pandas

- Plotted daily closing prices for all companies on a single chart
  (2010--2024)

- Calculated total return using start and end prices for each stock

- Measured average daily volatility using the standard deviation of
  daily returns

- Answered key business questions through Markdown explanations and
  visuals

**📂 File Structure**

business-data-project/

├── data/

│ └── stock_data.csv

├── analysis.ipynb \# Main Jupyter Notebook

├── analysis.html \# Exported HTML version

├── requirements.txt \# Python dependencies

└── README.md \# Project summary (this file)

**Collaborator**

- **Justin Lekwuwa**

**How to Run This Project in Visual Studio Code**

1.  **Clone the Repository**

git clone https://github.com/Jaytalk/business-analysis-project.git

2.  **Open the Folder in VS Code**

> Go to File \> Open Folder and select the downloaded project folder.

3.  **Install VS Code Extensions**

> Install:

- Python

- Jupyter

4.  **Install Required Libraries**

> Run the following in the terminal:

pip install -r requirements.txt

5.  **Open and Run the Notebook**

- Open analysis.ipynb

- Use Shift + Enter to run cells or click Run All
