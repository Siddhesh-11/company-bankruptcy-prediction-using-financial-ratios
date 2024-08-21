# Company Bankruptcy Prediction Using PySpark

## Project Overview

This project aims to develop a machine learning model using PySpark to predict the likelihood of a company filing for bankruptcy. By leveraging PySpark's distributed computing capabilities, the project efficiently handles large datasets of financial information and builds a robust classification model to identify companies at high risk of bankruptcy.

## Objectives

- Utilize PySpark to process and analyze large financial datasets.
- Develop a classification model to predict company bankruptcy.
- Evaluate model performance using relevant metrics.
- Identify key financial factors contributing to bankruptcy risk.

## Data

### Internal Data

The project utilizes a pre-existing dataset containing various financial metrics, including:

- **ROA (C) before interest and depreciation**: Return on Assets before interest and depreciation.
- **Operating Gross Margin**: Ratio of gross profit to sales revenue.
- **Current Ratio**: Measure of a company's ability to meet short-term obligations.
- **Quick Ratio**: A more stringent measure of liquidity than the current ratio.
- **Debt Ratio (%)**: Ratio of total liabilities to total assets, indicating financial leverage.
- **After-tax Net Profit Growth Rate**: Percentage change in net profit over a period.

### External Data (Optional)

The project also considers incorporating additional financial data from Yahoo Finance using the `yfinance` library, including:

- Stock price history
- Market capitalization
- Other relevant financial ratios

### Constraints

- **Data Availability**: Access to historical financial data, especially for companies that have already filed for bankruptcy, may be limited by API usage restrictions or data availability.

## Team Members

- Sharjeel Nawaz
- Siddhesh Mishra
- Tirth Shah

## Installation

To run this project, you need to install the following packages:

```bash
pip install pyspark
pip install kaggle
