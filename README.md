**Python • Pandas • Plotly • Cufflinks • Matplotlib**

---

## **Background**

Bitcoin is the most prominent cryptocurrency in the world, known for its extreme price volatility and explosive growth over the last decade. Understanding its historical behavior can offer critical insights into investment patterns, market cycles, and forecasting strategies.

This project performs an in-depth analysis of Bitcoin's historical price data from 2013 to 2017. The goal is to uncover long-term trends, volatility patterns, and statistical insights using Python-based tools and interactive visualizations.

**Key questions investigated:**

- How has Bitcoin's closing price evolved over time?
- What trends emerge at yearly, quarterly, and monthly scales?
- How volatile is Bitcoin on a day-to-day basis?
- Can we better visualize changes using log scaling and candlestick charts?

---

## **Main Objectives**

This project answers key time-series and financial questions through analysis and visualizations:

1. **How has Bitcoin's price changed over time?**
2. **What is the average price movement on different time scales (year, quarter, month)?**
3. **How volatile are daily returns, and what tools best show this?**

---

## Dataset

- **Bitcoin Historical Prices:** A CSV file containing daily `Open`, `High`, `Low`, `Close`, and `Date` values for Bitcoin from April 2013 to July 2017.

---

## Workflow Overview

- Imported and cleaned the Bitcoin price dataset using Pandas.
- Converted the `Date` column to a datetime format and set it as the DataFrame index.
- Visualized price trends using line plots and candlestick charts.
- Resampled the data to analyze average prices on different time frequencies.
- Calculated and plotted daily return percentages.
- Created both static (Matplotlib) and interactive (Plotly & Cufflinks) visualizations.

---

## Tools & Libraries Used

**Python (Jupyter Notebook):** For data cleaning, time series processing, return calculation, and plotting.

Key libraries:

- `pandas` – Data manipulation and time series resampling
- `numpy` – Numeric calculations (log transforms, pct change)
- `matplotlib`, `seaborn` – Static data visualizations
- `plotly`, `cufflinks` – Interactive charts (candlestick and returns)
- `chart_studio` – Hosting and rendering Plotly visuals

---

## Key Insights

- **Consistent Upward Trend:** Bitcoin showed steady growth between 2013 and 2017, with notable increases from 2016 onward.
- **No Seasonality:** The data does not display cyclical or seasonal price trends.
- **Extreme Volatility:** Day-to-day returns can vary dramatically, underscoring Bitcoin’s high-risk, high-reward nature.
- **Log Scale Benefits:** Using logarithmic price scaling improved visibility of earlier values and relative growth patterns.
- **Time-based Aggregation:** Yearly, quarterly, and monthly resampling revealed clearer long-term price trends, smoothing daily noise.

---

## Project Visualizations

**Price Trends Over Time:** Used line plots to show `Open`, `High`, `Low`, and `Close` across the dataset, revealing the steep upward momentum in Bitcoin’s value.

**Candlestick Chart (First 50 Days):** Used Plotly to create a candlestick chart for a sample time period. This helped visualize intraday volatility and the relationship between `Open`, `High`, `Low`, and `Close`.

**Daily Returns:** Calculated and plotted the daily percentage change in closing price to measure volatility. Used Cufflinks to make the chart interactive with zoom and hover effects.

**Resampled Views:** Resampled the closing price data by:

- **Year (`'YE'`)** – Annual average closing prices
- **Quarter (`'QE'`)** – Smoothed quarterly trends
- **Month (`'ME'`)** – Finer-grained trend analysis

---

## Skills Demonstrated

- Time series analysis and visualization
- Data cleaning and datetime manipulation
- Financial return calculation and trend detection
- Interactive dashboard-style visuals using Plotly and Cufflinks
- Log scaling and volatility analysis

---

## Conclusion

This case study demonstrates how Python can be used to analyze and visualize financial data effectively. By leveraging time series techniques and interactive tools, we uncovered important trends in Bitcoin’s early growth years and highlighted its volatility. These methods can be scaled and applied to other cryptocurrencies or asset classes to support financial research and decision-making.
