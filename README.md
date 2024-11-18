
# Crude Oil Price Analysis Using Hopping Window Strategy

Welcome to the **Crude Oil Price Analysis** repository! This project demonstrates how to analyze **West Texas Intermediate (WTI) Crude Oil Prices** using a **hopping window strategy**. By leveraging Python, we calculate weekly metrics such as the **mean** and **maximum crude oil prices**, while using overlapping time windows to gain deeper insights.

---

## 📃 Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Dataset](#dataset)
4. [Installation](#installation)


---

## 📌 Project Overview

Crude oil prices are vital indicators of global economic trends and energy markets. This project provides a clear approach to analyzing WTI crude oil prices by using a **hopping window** strategy to calculate:
- Weekly average prices.
- Weekly maximum prices.

The hopping window strategy is particularly useful for tracking overlapping trends across smaller time intervals, giving more granular insights compared to fixed windows.

---

## ✨ Features

- **Dynamic Hopping Window Metrics**: Calculate overlapping weekly metrics using adjustable time frames (e.g., 7-day window, 3-day hop).
- **Seamless Data Processing**: Includes data cleaning and preprocessing for real-world datasets.
- **Export Results**: Outputs metrics to an Excel file for easy sharing and further analysis.
- **Colab Integration**: Fully compatible with Google Colab for cloud-based execution.

---

## 📊 Dataset

The dataset used in this project contains:
- **Crude Oil Prices** (WTI) from [Cushing, Oklahoma](https://fred.stlouisfed.org/series/DCOILWTICO).
- **Date Range**: Includes daily prices in USD per barrel.

### Sample Data Format:
| Date       | Price (USD) |
|------------|-------------|
| 2019-10-28 | 55.6        |
| 2019-10-29 | 55.34       |
| 2019-10-30 | 54.85       |

---

## 🚀 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/subhashpolisetti/CrudeOilAnalysis_HoppingWindow.git

## 📈 Results

The project outputs an Excel file with the calculated metrics. Each row contains:
- **Start and End Dates** of the window.
- **Mean Price**: Average crude oil price for the window.
- **Max Price**: Highest crude oil price for the window.

Example:
| Window Start | Window End   | Mean Price | Max Price |
|--------------|--------------|------------|-----------|
| 2019-10-28   | 2019-11-03   | 55.17      | 56.04     |
| 2019-10-31   | 2019-11-06   | 55.92      | 57.04     |

---

