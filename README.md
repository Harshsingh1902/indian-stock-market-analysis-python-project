#  Financial Analysis of Indian Stock Market Indices Using Python



### Harsh Kumar Singh


### Indroduction
Python has achieved a paramount position in the financial sector, driven by its exceptional adaptability, computational efficacy, and a broad, specialized library ecosystem. Its inherent clarity and seamless integration capabilities establish it as the definitive programming language for the rapid construction and deployment of sophisticated quantitative models, substantially enhancing capabilities across the finance industry.The central objective of this endeavor is to develop an in-depth, applied instructional guide utilizing Python for rigorous financial analysis. The scope of the study will concentrate on leveraging key libraries to evaluate the historical market behavior and risk exposure of leading Indian Stock Market Indices specifically the benchmark Nifty 50 (NSEI), the foundational BSE Sensex (BSESN), and the sector-specific Nifty Bank (NSEBANK) spanning the years 2017 through 2024.The deliverable of this project will be a methodological, step-by-step framework for processing financial time-series data, precisely quantifying critical performance indicators such as Annualized Volatility and Cumulative Returns, and graphically representing these findings to deliver a comprehensive market assessment.
## Motivation
This project helps understand the dynamics, risk, and performance of key Indian stock market indices over time. It provides insights into market behavior during high-stress periods such as the COVID-19 crash and guides investment decisions by comparing benchmarks.

### Background
For this project, my focus is on conducting a comprehensive analysis of the performance, risk, and dynamics of the Indian Stock Market over a five-year period that includes significant market cycles.

To achieve this, I will perform a thorough financial analysis of various key stock indexes across India, more precisely:

Nifty 50 (^NSEI): (The benchmark index of the National Stock Exchange (NSE), representing the 50 largest Indian companies.)

BSE Sensex (^BSESN): (The benchmark index of the Bombay Stock Exchange (BSE), representing the top 30 blue-chip Indian companies.)

Nifty Bank (^NSEBANK): (The index of the Indian banking sector, tracking the performance of the most liquid and large-capitalized Indian banking stocks.)

I plan to collect historical stock data from 2017 to 2024, aiming to recognize patterns and trends in market performance and volatility. Through a detailed analysis of metrics like Returns and Annualized Volatility, I aim to extract valuable insights that can shed light on the dynamics of the Indian equity market, providing a comprehensive understanding of the risk-reward trade-offs during this period.

### Project Outline 
## Outline

* Importing the data
    - installing yfinance library
    - creating a dataframe
* Exploratory Data Analysis
* Data Visualization    
    - Missing Values Visualization
    - Line Charts
    - Candlestick Charts
* Financial Analysis 
    - Daily Returns
    - Average Daily Returns 
    - Volatility

##  Project Overview

This project provides a **comprehensive analysis of key Indian stock market indices** using Python.  
It evaluates **market trends, returns, volatility, risk, and correlations** using historical data from:

- Nifty 50 (^NSEI) – Benchmark of NSE (50 largest companies)
- BSE Sensex (^BSESN) – Benchmark of BSE (top 30 blue-chip companies)
- Nifty Bank (^NSEBANK) – Sector-specific index for Indian banking stocks

**Time Period Analyzed:** 2017 – 2024

The project leverages Python libraries such as **pandas, NumPy, yfinance, Matplotlib, Seaborn, Plotly, and missingno** to extract, process, visualize, and analyze financial data.

---

##  Objectives

- Fetch historical stock market data using Python
- Perform Exploratory Data Analysis (EDA)
- Visualize price movements and market trends
- Analyze returns, volatility, drawdowns, and risk-adjusted performance
- Study market behavior during high-stress periods (e.g., March 2020 COVID-19 crash)

---

##  Methodology

1. **Data Collection**
   - Download historical price data using the `yfinance` library
   - Data includes Open, High, Low, Close, and Volume

2. **Data Cleaning & Preparation**
   - Combine indices into a single DataFrame
   - Handle missing data using `missingno` visualization

3. **Exploratory Data Analysis**
   - Check shape, info, and descriptive statistics
   - Identify missing data and outliers

4. **Data Visualization**
   - Line charts to track long-term price trends
   - Candlestick charts for detailed price movements
   - Visualize missing data and correlations

5. **Financial Analysis**
   - Daily returns
   - Cumulative returns
   - Annualized volatility
   - Maximum drawdown
   - Sharpe ratio
   - Correlation analysis between indices

---

## Key Metrics Calculated

- **Daily Returns** – Percentage change in closing prices
- **Cumulative Returns** – Growth of investment over time
- **Volatility** – Standard deviation of daily returns
- **Sharpe Ratio** – Risk-adjusted return
- **Maximum Drawdown** – Largest observed loss from peak to trough
- **Correlation Matrix** – Relationship between indices

---

## Tools & Libraries Used

- Python
- pandas
- NumPy
- yfinance
- Matplotlib
- Seaborn
-  Plotly
- missingno
- Google collab

  ## Installation
1. Clone the repository:
   git clone https://github.com/Harshsingh1902/indian-stock-market-analysis-python-project.git
2. Navigate to the project folder:
   cd financial-analysis-india
3. Install dependencies:
   pip install pandas numpy yfinance matplotlib seaborn plotly missingno
4. Open Jupyter Notebook or Google Colab to run analysis

## 📄 Project Report (HTML)
Click below to view the full analysis report:
👉 (https://harshsingh1902.github.io/indian-stock-market-analysis-python-project/)
## Visualizations

This section presents the key visual outputs from the financial analysis, illustrating market trends, price action, risk profiles, and index interdependencies across the Nifty 50 (^NSEI), BSE Sensex (^BSESN), and Nifty Bank (^NSEBANK) from 2017 to 2024.

---

### **1. Price Trends and Historical Performance**

These line charts provide a clear overview of the cumulative growth and major historical events for each index over the analysis period.




This chart displays the adjusted closing price trajectories for all three indices on a single scale. It highlights the strong bull run from 2020 onwards and the simultaneous significant drop experienced by all indices in March 2020 due to the global pandemic.
<img width="1102" height="697" alt="adjusted price over time" src="https://github.com/user-attachments/assets/52726887-46e5-4b73-877c-4a322385b038" />

---

#### **Closing Stock Prices Over Time**

Similar to the adjusted prices, this plot shows the raw closing prices. Observing both adjusted and unadjusted prices confirms the overall sustained upward trend and the common market response to major global events, demonstrating the co-movement of the top Indian indices.
<img width="1105" height="701" alt="closing stock price over time" src="https://github.com/user-attachments/assets/18d9557b-de51-4691-9b87-59468a8b251f" />


---

### **2. Candlestick Price Action and Volatility**

Candlestick charts offer a granular view of daily price movements, helping to identify short-term volatility, market sentiment, and key reversal patterns, particularly during the high-stress period of early 2020.

#### **Candlestick Chart of Nifty 50 Prices (2017-2024)**

This comprehensive candlestick chart for the Nifty 50 illustrates the long-term price action, showing periods of consolidation followed by strong breakouts. The deep, sharp drop around early 2020 is clearly visible, emphasizing the market's reaction to systemic risk.
<img width="1340" height="525" alt="candle chart nse prices" src="https://github.com/user-attachments/assets/04f3eb1f-1871-46a6-ae6c-6420126e6c12" />

---

#### **Nifty 50 Candlestick Chart: January-June 2020**

A focused view on the first half of 2020, this chart vividly captures the dramatic price collapse in March and the subsequent recovery phase. This period is critical for analyzing extreme volatility and investor reaction during a Black Swan event.

<img width="1017" height="525" alt="Candelstick chart jan-jun 20" src="https://github.com/user-attachments/assets/743cdd14-6b7a-49f2-a3dc-c7ba243d8f1e" />

---

#### **Nifty 50 Candlestick Chart: March 2020**

Zooming in on the most turbulent month, this chart provides a day-by-day visualization of the price war. It highlights days of extreme selling pressure (long red bodies) and subsequent days with significant uncertainty or attempted rebounds (long wicks/smaller bodies).

<img width="1340" height="525" alt="candle chart nse" src="https://github.com/user-attachments/assets/dbaa37e2-1c1f-4887-8096-80df2409fd4d" />

---

#### **Candlestick Charts for Selected Indian Indices - March 2020**

This grouped chart allows for a side-by-side comparison of the Nifty 50, BSE Sensex, and Nifty Bank price action during the high-volatility March 2020 period. It underscores the synchronized nature of the sell-off across the benchmark and sectoral indices.

<img width="1340" height="525" alt="candle chrt for slctd 2020" src="https://github.com/user-attachments/assets/07e32776-4270-49dc-bcfd-db476307b57c" />


---

### **3. Returns and Risk Analysis**

These visualizations are central to quantifying risk and performance, focusing on the dispersion and magnitude of daily returns.

#### **Combined Daily Returns Analysis**

This plot superimposes the daily returns for all three indices. It visually confirms that periods of high return-volatility are highly correlated across all indices, with the most extreme fluctuations occurring around early 2020.


<img width="1017" height="525" alt="daily return ana" src="https://github.com/user-attachments/assets/1cc7e0a4-4a3e-49f0-bbeb-388eb35f0e31" />


#### **Individual Daily Returns Analysis**

Separating the daily returns for each index provides a cleaner look at their individual return distribution over time. This separation allows for a quick visual assessment of which index may exhibit greater daily swings (e.g., ^NSEBANK often shows marginally higher return spikes).
<img width="1017" height="525" alt="daily return analysis" src="https://github.com/user-attachments/assets/964f0d7e-0fbf-4a8f-abdb-517e6a067406" />


---

### **4. Data Quality Check**

#### **Missing Data Visualization**

These matrix plots are a crucial step in data cleaning. The filled areas (blue/red) confirm that there are no missing values for the key financial metrics (Close, High, Low, Open, Volume) across the analysis period for both Nifty 50 and the combined Indian indices.

<img width="1919" height="900" alt="missing data visualization nse" src="https://github.com/user-attachments/assets/97a6dd09-5f47-47ee-9447-e492001cf61a" />

<img width="1919" height="950" alt="missing data visualization indian indices" src="https://github.com/user-attachments/assets/6c5c8381-0d68-44a3-91a7-e1f82e732f72" />


## Key Insights
- NSEBANK index exhibited the **highest volatility** among indices.
- Nifty 50 and Sensex showed **strong correlation**, indicating market-wide trends.
- March 2020 COVID-19 crash affected all indices, with NSEBANK suffering the largest drawdown.

### Conclusion
In conclusion, this comprehensive tutorial has provided a foundational understanding of applied financial analysis using Python, offering a step-by-step guide to leveraging powerful libraries such as yfinance, pandas, and Plotly.

We started by successfully fetching historical stock data for the key Indian Stock Market IndicesNSEI, BSESN, and NSEBANK spanning the critical 2017–2024 period. This process allowed us to directly examine market behavior during both growth phases and periods of high stress, such as the synchronized market crash in March 2020.

We explored and calculated key financial metrics, including Daily Returns and Annualized Volatility, revealing that the sector-specific NSEBANK index exhibited the highest risk profile. The tutorial also demonstrated how to create insightful visualizations, such as comparative line plots and time-sensitive candlestick charts, to enhance data interpretation.

By employing practical examples and hands-on coding exercises focused on real-world Indian market data, this tutorial equips you with the essential tools and skills to conduct a robust financial analysis, providing quantitative information regarding the risk and return characteristics of different investment benchmarks.

## Future Scope
- Extend analysis to sector-specific indices (IT, Pharma, FMCG)
- Forecast trends using ARIMA or LSTM models
- Build interactive dashboards with Plotly Dash or Streamlit
- Portfolio optimization and risk-return simulations

## References 



Yahoo Finance (via yfinance)

Python libraries documentation

Investopedia for definitions

---


