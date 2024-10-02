# Time-series-investigation-of-bitcoin-Applying-CAPM

Here’s a draft of a **README** for your GitHub repository that includes the content from the *Correlation and CAPM Analysis* and other elements you might need to include:

---

# Correlation and CAPM Analysis with Time Series Investigation

## Overview

This repository contains financial analysis and modeling projects focusing on the correlation between different asset classes, Capital Asset Pricing Model (CAPM) analysis, and time series investigation. The following key components are included:

1. **Correlation and CAPM Analysis** - A comprehensive study of Bitcoin, bonds, and the S&P 500, examining their correlations and performing a CAPM regression on Bitcoin to assess its systematic risk (beta) and excess returns (alpha).
2. **Time Series Investigation of Bitcoin Price** - A Jupyter notebook that analyzes the price of Bitcoin over time using various statistical and machine learning methods.
3. **FRED API Data Extraction** - A Python notebook demonstrating how to extract financial data from the Federal Reserve Economic Data (FRED) API for further analysis.

## Files

1. **[Correlation and CAPM Analysis.pdf](./Correlation%20and%20CAPM%20Analysis.pdf)**  
   This PDF report investigates the correlation between Bitcoin, bonds, and the S&P 500 index. The study performs CAPM regression to calculate Bitcoin’s beta and alpha, assessing its volatility compared to the market.

   **Key Results:**
   - Bitcoin exhibits weak correlation with the stock market and almost no correlation with bonds.
   - CAPM regression shows Bitcoin has a beta of 1.0860, indicating it is a high-risk, high-return asset.
   - Alpha is close to zero, meaning Bitcoin does not provide significant excess returns.

2. **[Time Series Investigation of Bitcoin Price.ipynb](./Time%20Series%20Investigation%20of%20Bitcoin%20Price.ipynb)**  
   This Jupyter notebook explores time series methods to analyze Bitcoin's price. The notebook employs techniques like ARIMA models and other time series forecasting approaches to predict future price movements based on historical data.

3. **[FRED API Data Extraction.ipynb](./FRED%20API%20Data%20Extraction.ipynb)**  
   A Python notebook that demonstrates how to use the FRED API for extracting macroeconomic data for various financial analyses. This can be particularly useful for acquiring interest rates, inflation data, and other economic indicators directly from FRED.

## Setup and Requirements

To run the notebooks in this repository, you'll need the following packages installed in your Python environment:

- **pandas**  
- **numpy**  
- **statsmodels**  
- **matplotlib**  
- **seaborn**  
- **yfinance** (for financial data extraction)  
- **fredapi** (for FRED API access)

You can install the necessary packages by running:

```bash
pip install pandas numpy statsmodels matplotlib seaborn yfinance fredapi
```

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/repositoryname.git
   ```
2. Install the dependencies listed in the `requirements.txt` file or using the pip command above.
3. Open the Jupyter notebooks (`*.ipynb`) in your preferred environment (e.g., JupyterLab, Google Colab) to explore the analysis.

## Contributions

Feel free to open issues or submit pull requests if you would like to improve or extend the analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Let me know if you want to add any other specific details or modify this draft!
