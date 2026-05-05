# Paijo Reports — Stock Analysis YTD 2026

Automated YTD stock market analysis report for 79 tickers (IDX LQ45 + US majors + Global).

Live: https://paijo-bot.github.io/stock-report/

## Data
- Period: Jan 1 — May 5, 2026
- Source: Yahoo Finance (yfinance)
- Analysis: Manual + data-driven anomaly detection
</EOF>

git add .
git commit -m "Initial: YTD stock analysis report" 2>&1

# Create GitHub repo via gh CLI
echo "---"
gh repo create stock-report --public --push --source=. --remote=origin --description "YTD Stock Market Analysis Report — May 5, 2026" 2>&1
