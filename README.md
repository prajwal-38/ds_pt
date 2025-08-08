# Market Sentiment vs Trading Behavior Analysis

## Project Overview

This project examines how Bitcoin market emotions (Fear & Greed Index) relate to actual trading patterns on Hyperliquid exchange. The goal is finding profitable trading opportunities based on market psychology.

## Dataset Information

**Fear & Greed Index Data:**
- Daily sentiment scores from 2018-2024
- 2,646 records with classifications (Extreme Fear to Extreme Greed)

**Hyperliquid Trading Data:**
- 211,226 individual trades from December 2024
- Includes account info, trade sizes, profits/losses, timestamps

## Setup Instructions

Install required packages:
```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

Run the analysis:
1. Open notebooks in Google Colab
2. Upload CSV files from `csv_files/` folder
3. Execute all cells in order

## Project Structure

```
ds_user/
├── notebook_1.ipynb          # Main sentiment analysis
├── notebook_2.ipynb          # Advanced risk analytics
├── csv_files/                 # Data files
├── outputs/                   # Charts and graphs
├── TRADING_CONCEPTS_EXPLAINED.md     # Trading basics
├── DATA_SCIENCE_CONCEPTS_EXPLAINED.md # Technical concepts
├── NOTEBOOK_1_CODE_EXPLAINED.md      # Code walkthrough
├── NOTEBOOK_2_CODE_EXPLAINED.md      # Advanced code
└── README.md                  # This file
```

## What the Analysis Does

**Notebook 1 - Core Analysis:**
- Shows how sentiment changes over time
- Compares trading volume during different emotions
- Tests contrarian vs momentum strategies
- Analyzes hourly and daily trading patterns

**Notebook 2 - Advanced Analytics:**
- Uses machine learning to classify risk periods
- Calculates Value at Risk and other risk metrics
- Finds hidden patterns with PCA analysis
- Creates sophisticated trading signals

## Key Findings

**During Extreme Fear:**
- Higher trading volumes
- Better opportunities for contrarian buying
- More volatile but potentially profitable

**During Extreme Greed:**
- Risk of momentum traps
- Good time for profit-taking
- Lower efficiency per dollar traded

**Time Patterns:**
- Certain hours show higher activity
- Weekend trading behaves differently
- Weekly cycles affect profitability

## Documentation Files

**For Beginners:**
- `TRADING_CONCEPTS_EXPLAINED.md` - Basic trading terms and concepts
- `DATA_SCIENCE_CONCEPTS_EXPLAINED.md` - Statistics and ML basics

**Code Explanations:**
- `NOTEBOOK_1_CODE_EXPLAINED.md` - Line-by-line code walkthrough
- `NOTEBOOK_2_CODE_EXPLAINED.md` - Advanced techniques explained

## Technical Features

- Interactive charts with zoom and hover
- Professional dark theme styling
- Statistical significance testing
- Machine learning pattern recognition
- Risk-adjusted performance metrics

## Notes

The analysis uses real trading data to test whether market sentiment can predict profitable trading opportunities. All strategies are backtested on historical data, but past performance doesn't guarantee future results.

**Warning:** Trading involves significant risk. This analysis is for educational purposes only.
