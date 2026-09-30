# Sequence of Returns Safe Withdrawal Sim
Monte Carlo SWR simulation showing portfolio survival probability across 30-year retirement scenarios. Input: initial portfolio, annual withdrawal %, average return, std dev. Run 500 simulations. Show: survival %, histogram of final balances, percentile lines.

## Features
- 500-run Monte Carlo simulation using Box-Muller normal distribution
- Configurable inputs: initial portfolio, annual withdrawal %, avg return %, std deviation %
- Survival rate percentage (portfolio lasts all 30 years)
- Median and average final balance display
- 30-year trajectory chart with P10/P25/P50/P75/P90 percentile lines (canvas)
- Final balance histogram of surviving portfolios (canvas)
- Sequence-of-returns risk visualization
- Accessible inputs with aria-labels
