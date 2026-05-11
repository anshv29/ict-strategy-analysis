# ICT Strategy Analysis
### Does Smart Money Beat the Market?

A quantitative research project statistically evaluating whether popular 
retail trading strategies outperform passive investing, with long-term profit as the goal, after realistic assumptions.

**Asset:** SPY (S&P 500 ETF)  
**Period:** 2014–2024  
**Benchmark:** Passive Buy & Hold  

---

## Research Question
Do ICT/Smart Money Concepts and popular technical strategies actually 
beat simply buying and holding an index fund?

---

## Key Insight
Both strategies share the same fundamental weakness, they spend too much 
time out of the market. While passive buy and hold compounds quietly every 
single day, these strategies sit in cash missing the majority of long-term gains.

---

## Findings

## Findings

### Finding #1 — SMA Crossover (Golden/Death Cross)
The Golden/Death Cross strategy (50/200-day SMA) returned **48%** 
over 2018-2024 versus **95.5%** for passive buy and hold.

### Finding #2 — ICT Fair Value Gaps (Predictive Power)
Bullish FVG signals produced an average 5-day forward return of **0.066%** 
versus **0.278%** on non-FVG days — showing no positive predictive edge.

### Finding #3 — ICT FVG Strategy (Backtest)
The FVG trading strategy returned **25%** over 2014-2024 versus **211.3%** 
for passive buy and hold — an underperformance of **186.4%**.

### Finding #4 — Risk-Adjusted Returns (Sharpe Ratio)
Buy & Hold Sharpe: **0.737** vs FVG Strategy Sharpe: **0.320** — 
passive investing wins on a risk-adjusted basis too.

### Finding #5 — Maximum Drawdown
FVG Strategy: **-18.5%** vs Buy & Hold: **-33.7%** — the only metric 
where FVG shows an advantage, entirely due to being out of the market 88% of the time.

### Finding #6 — Win Rate
FVG win rate of **58.1%** sounds reasonable but is misleading without 
context of win/loss size.

### Finding #7 — Risk/Reward Analysis
Average win: **1.090%** vs average loss: **-1.356%** — the strategy 
wins more often but loses more per losing trade than it gains per winning trade.

---

## Tools Used
- Python, pandas, numpy, matplotlib, yfinance
- Jupyter Notebooks

---

## Limitations & Future Work
- Transaction costs only partially accounted for
- Single asset tested (SPY only)
- Future: test on QQQ, BTC, bear market periods, different FVG parameters

## Disclaimer
This project is for educational and research purposes only. 
Nothing here constitutes financial advice.
