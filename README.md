# NIFTY 50 Stock Data Exploratory Data Analysis (EDA)

## Overview
This project performs an **Exploratory Data Analysis (EDA)** on the NIFTY 50 stock dataset. The analysis covers various statistical and visualization techniques to gain insights into stock price movements, correlations, and distributions.

## Dataset
- The dataset used in this project is `NIFTY50_all.csv`.
- It includes columns such as **Open, High, Low, Close, Volume**, and **Symbol**.
- Missing values are handled by dropping them.

## Steps in the Analysis
### 1. **Data Loading & Cleaning**
- The dataset is loaded into a pandas DataFrame.
- Basic statistics and missing values are checked.
- Rows with missing values are removed.

### 2. **Univariate Analysis**
- **Histogram**: Distribution of `Close` and `Open` prices.
- **Boxplot**: Shows the spread and outliers in `Close` prices.
- **Pie Chart**: Displays stock volume distribution among the top 10 stocks.
- **Bar Chart**: Frequency of stocks based on symbols.

### 3. **Multivariate Analysis**
- **Correlation Heatmap**: Shows relationships between numerical variables.
- **Scatterplot**: Analyzes the relation between `Open` and `Close` prices.
- **Moving Average Plot**: Tracks trends in closing prices.
- **Stacked Area Plot**: Displays `Open`, `High`, `Low`, and `Close` prices over time.
- **2D Histogram**: Highlights the density of `Open` vs `Close` prices.
- **Staircase Plot**: Visualizes price movements over time.

## Visualizations Included
✔ Histograms 📊  
✔ Boxplots 📦  
✔ Scatterplots 📍  
✔ Heatmaps 🔥  
✔ Pie Charts 🥧  
✔ Bar Graphs 📏  
✔ Staircase Plots 📊  


## How to Run the Code
1. Ensure you have Python installed along with the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Run the Python script in a Jupyter Notebook or any Python environment.
3. The cleaned dataset will be saved as `NIFTY50_cleaned.csv`.

## Conclusion
This analysis provides a **comprehensive view of NIFTY 50 stock movements**, identifying trends, distributions, and correlations among different stock prices. 📈📉

---
### Author
This project was created to assist in financial data visualization and analysis using Python.

Happy Analyzing! 🚀

