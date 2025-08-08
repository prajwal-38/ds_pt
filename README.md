# Market Sentiment vs Trading Behavior Analysis

## Project Overview

This project examines how Bitcoin market emotions (Fear & Greed Index) relate to actual trading patterns on Hyperliquid exchange. The goal is finding profitable trading opportunities based on market psychology.

## Dataset Information

**Fear & Greed Index Data:**
- Records with classifications (Extreme Fear to Extreme Greed)

**Hyperliquid Trading Data:**
- Includes account info, trade sizes, profits/losses, timestamps

## Setup Instructions

Install required packages:
```bash
pip install pandas numpy matplotlib seaborn plotly jupyter kaleido pillow
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
└── README.md                  
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


## Technical Features

- Interactive charts with zoom and hover
- Professional dark theme styling
- Statistical significance testing
- Machine learning pattern recognition
- Risk-adjusted performance metrics

