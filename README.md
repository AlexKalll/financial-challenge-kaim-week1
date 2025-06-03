# KAIM - WEEK1
## Predicting Price Moves with News Sentiment 

Welcome to the Week 1 challenge project of the 10 Academy KAIM program. This repo explores a powerful idea in financial analytics: **can the tone of news headlines predict stock market moves?**

This project combines Natural Language Processing (NLP), technical stock indicators, and statistical analysis to investigate the relationship between financial news sentiment and stock price behavior.

---

## Project Overview

**Objective**: Analyze news headlines to extract sentiment, compare it with daily stock returns, and uncover actionable trading signals.

**Business Context**: Nova Financial Solutions wants to enhance forecasting by integrating financial sentiment and technical indicators into their strategy.

---

## Tasks Completed

### Task 1: GitHub & EDA

* Configured project structure and GitHub Actions CI pipeline
* Explored headline length, publishing trends, and publisher activity
* Identified topic keywords from headlines

### Task 2: Quantitative Analysis

* Loaded stock price data with Open/High/Low/Close/Volume
* Calculated technical indicators (SMA, RSI, MACD) using **TA-Lib** and **PyNance**
* Visualized market behavior with indicators overlayed on price data

### Task 3: Sentiment & Correlation

* Extracted sentiment scores from headlines using **TextBlob**
* Aligned sentiment with daily stock returns
* Measured correlation using **Pearson's coefficient**

---

## Key Technologies and tools used

* `Python`, `Pandas`, `Matplotlib`, `Seaborn`
* `TA-Lib`, `PyNance` for financial indicators
* `TextBlob`, `nltk` for sentiment scoring
* GitHub Actions CI for code quality

---

## Highlights

* Found a **moderate positive correlation (r = 0.32)** between sentiment and stock returns
* Morning headlines (7-11AM) showed stronger impact on price behavior
* Visualized news + technical signals for smarter trade insights

---

## How to have a trial

```bash
# Clone the repo
https://github.com/AlexKalll/financial-challenge-kaim-week1

# Install dependencies
pip install -r requirements.txt

# Explore Jupyter Notebooks in notebooks/
Nb. I highly recommend to install Ta-lib manullay to be safe
```

---

## Let's get in toutch

**Kaletsidik Ayalew** – alexkalalw@gmail.com
