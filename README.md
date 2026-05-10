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
Both strategies share the same fundamental weakness — they spend too much 
time out of the market. While passive buy and hold compounds quietly every 
single day, these strategies sit in cash missing the majority of long-term gains.

---

## Findings

### Finding #1 — SMA Crossover (Golden/Death Cross)
The Golden/Death Cross strategy (50/200-day SMA) returned **48%** 
over 2018-2024 versus **95.5%** for passive buy and hold. Essentially, 
the strategy lost to doing nothing by nearly double. 

### Finding #2 — ICT Fair Value Gaps (Does the Signal truly predict what it claims?)
Bullish FVG signals produced an average 5-day forward return of **0.066%** 
versus **0.278%** on non-FVG days — showing no positive predictive edge. 

### Finding #3 — ICT Fair Value Gap Strategy (Backtest)
The FVG trading strategy returned **25%** over 2014-2024 versus **211.3%** 
for passive buy and hold — an underperformance of **186.4%**. 

---

## Tools Used
- Python, pandas, numpy, matplotlib, yfinance
- Jupyter Notebooks

---

## Project Structure
notebooks
├── 02_backtest.ipynb        # SMA crossover baseline backtest
└── 03_ict_signals.ipynb     # ICT Fair Value Gap signal detection

---

## Limitations & Future Work
- Transaction costs only partially accounted for
- Single asset tested (SPY only)
- FVG definition is one interpretation — ICT concepts are intentionally vague
- Future: test on QQQ, BTC, bear market periods, different FVG parameters

## Disclaimer
This project is for educational and research purposes only. 
Nothing here constitutes financial advice.