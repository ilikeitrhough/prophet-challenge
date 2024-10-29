# MercadoLibre Search Traffic and Stock Analysis

## Overview

This project involves analyzing MercadoLibre's Google search traffic data and stock price data to uncover patterns, relationships, and build predictive models using time series analysis. The goal is to determine if search traffic can predict stock price movements and to provide insights for marketing and financial strategies.

## Table of Contents

- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Analysis Steps](#analysis-steps)
  - [Step 1: Analyzing Unusual Patterns in Search Traffic](#step-1-analyzing-unusual-patterns-in-search-traffic)
  - [Step 2: Mining Search Traffic Data for Seasonality](#step-2-mining-search-traffic-data-for-seasonality)
  - [Step 3: Relating Search Traffic to Stock Price Patterns](#step-3-relating-search-traffic-to-stock-price-patterns)
  - [Step 4: Time Series Modeling with Prophet](#step-4-time-series-modeling-with-prophet)
- [Findings and Conclusions](#findings-and-conclusions)

## Dataset Description

- **Google Search Trends Data**: Hourly search traffic data for MercadoLibre.
- **Stock Price Data**: Historical stock prices of MercadoLibre.

## Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or Google Colab
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - prophet (for time series forecasting)

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/prophet-challenge.git

2. **Install Required Libraries**:
    ```bash
    pip install pandas numpy matplotlib prophet

## Analysis Steps
#### Step 1: Analyzing Unusual Patterns in Search Traffic
Objective: Identify any unusual patterns in the Google search data and determine if they correlate with MercadoLibre's financial events.

#### Step 2: Mining Search Traffic Data for Seasonality
Objective: Discover predictable seasonal patterns in the search traffic data to optimize marketing efforts.

#### Step 3: Relating Search Traffic to Stock Price Patterns
Objective: Investigate the relationship between search traffic and stock price movements.

#### Step 4: Time Series Modeling with Prophet**\
Objective: Build a time series model to forecast search traffic using Facebook's Prophet library.

## Findings and Conclusions
**Unusual Patterns:** Increased search traffic during May 2020 suggests public interest correlates with financial events.

**Seasonality:** Clear daily and weekly patterns can inform marketing strategies.

**Stock Relationship:** No significant correlation between search trends and stock volatility or returns in the short term.

**Forecasting:** The Prophet model provides valuable insights into future search trends, highlighting peak times and potential seasonal dips.

