# alpha-factor-research
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fatenahaq-blip/alpha-factor-research/blob/main/notebooks/alpha_factor_research.ipynb)

## Overview

This project investigates whether stocks with strong recent price performance continue to outperform stocks with weak recent price performance.

A six-month momentum signal is used to rank a sample of large US stocks. The analysis compares high-momentum and low-momentum portfolios and evaluates the long-short factor using risk and performance statistics.

## Research question

Do stocks with high trailing six-month returns outperform stocks with low trailing six-month returns during the following month?

## Methodology

1. Download adjusted daily stock prices.
2. Convert prices to month-end observations.
3. Calculate trailing six-month returns.
4. Lag the signal to reduce look-ahead bias.
5. Rank stocks cross-sectionally each month.
6. Select the highest and lowest 20%.
7. Form equal-weighted portfolios.
8. Calculate long, short and long-short returns.
9. Evaluate annual return, volatility, Sharpe ratio and drawdown.
10. Test information coefficients, turnover, transaction costs and alternative lookback periods.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- yfinance
- Google Colab
- GitHub

## Repository structure

```text
alpha-factor-research/
├── notebooks/
│   └── alpha_factor_research.ipynb
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
