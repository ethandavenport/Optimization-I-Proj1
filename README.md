# Optimization I Project 1: Portfolio Management, Linear Programming

## Links to code notebooks:

| Notebook        | Colab |
|-----------------|-------|
| `optimizer.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ethandavenport/Optimization-I-Proj1/blob/main/optimizer.ipynb) |


## In colab, if you make changes to notebooks, use "save in github" at the top of the page to re-commit.
## Download any created csv or other files and re-commit those manually.

| Task                           | What                                                                                                                             | File/Notebook | Done by | Date | Validated by | Notes / PR |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------- | ---- | ------------ | ---------- |
| **2. Optimal 2019 Portfolio**         | Find the portfolio that minimizes the daily average CVaR using the 2019 data. Use beta=0.95 and R=0.02%.                      |  |   Ethan      |   9/19   |              |       |
| **2a. 2020 CVaR**         | Recompute the 95%-CVaR for 2020 by evaluating the CVaR objective using the 2019-optimized x and 2020 returns.                      |  |         |      |              |       |
| **2b. NDX CVaR**         | Calculate the 95%-CVaR of the NDX index for the same periods (2019 in-sample and 2020 out-of-sample) for comparison.                      |  |         |      |              |       |
| **3. Different Beta Values**         | Re-run the 2019 CVaR minimization with β = 0.90 and β = 0.99 and describe how changing β shifts the portfolio allocations.                      |  |         |      |              |       |
| **4. Conservative Risk Management Approach**         | Replace the objective with minimizing the maximum monthly β-CVaR (the worst single-month tail loss) using 2019 data and compare that conservative monthly-max-CVaR portfolio to the portfolio from Part 2.                      |  |         |      |              |       |
| **5. Monthly Updates**         | Implement a rolling monthly re-optimization for 2020 (each month’s portfolio chosen using the previous 12 months of daily returns)                      |  |         |      |              |       |
| **6. Stable Portfolio**         | Check whether consecutive monthly portfolio weights change by no more than ±0.05 per instrument (i.e., stable)                      |  |         |      |              |       |
| **7. PDF Report Format**         | Produce a professionally formatted PDF report containing narrative, figures, and executable code chunks                      |  |         |      |              |       |
| **8. Read CSV and Generalizability**         | Include at the top of the main Python code chunk a visible pd.read_csv(...) call (clearly commented so graders know where to swap in new CSVs) and ensure all code is generalized.                      |  |         |      |              |       |
