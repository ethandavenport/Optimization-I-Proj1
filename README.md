🧮 Low-Risk Portfolio Optimization Project (2019–2020 Market Shock Analysis)
📚 Overview

This project evaluates risk-managed portfolio strategies across the 2019–2020 period, with a special focus on how portfolios perform during market disruptions like the COVID-19 pandemic. The primary goal is to minimize Conditional Value-at-Risk (CVaR) using daily return data from 100 Nasdaq-100 stocks.

We explore various risk models using historical returns, test their out-of-sample performance, and evaluate portfolio stability and adaptability over time. The analysis covers both annual and rolling monthly re-optimization techniques.

📁 Links to Code Notebooks
Notebook	Colab Link
Assignment_Portfolio_CVaR.ipynb	

cvar_optimizer.ipynb	

monthly_cvar_analysis.ipynb	

🔁 IMPORTANT: All code is written to dynamically adapt to any correctly-formatted dataset. Make sure your CSV file matches the required input format. You can swap in new data by changing the CSV in the pd.read_csv() line.

✅ Project Task Tracker
Task	Description	File/Notebook	Done by	Date	Validated by	Notes
Data Load + Return Calculation	Calculate daily returns from price CSVs; exclude NDX index column	cvar_optimizer.ipynb	[Name]	[Date]		CSV file read clearly marked
Task 2: Baseline CVaR (β=0.95)	Minimize average daily CVaR using 2019 returns; evaluate performance in 2020	cvar_optimizer.ipynb	[Name]	[Date]		Includes out-of-sample vs in-sample CVaR
NDX CVaR	Compute CVaR of Nasdaq index (for comparison)	cvar_optimizer.ipynb	[Name]	[Date]		
Task 3: Compare β values	Re-run 2019 optimization with β = 0.90 and β = 0.99	cvar_optimizer.ipynb	[Name]	[Date]		Charts and allocation comparisons included
Task 4: Max Monthly CVaR	Conservative approach: minimize worst month’s CVaR instead of average	cvar_optimizer.ipynb	[Name]	[Date]		New objective function implemented
Task 5: Monthly Rolling CVaR	Re-optimize portfolio each month using trailing 1-year window	monthly_cvar_analysis.ipynb	[Name]	[Date]		Includes summary stats for CVaR series
Task 6: Stability Check	Evaluate month-to-month stability (<= 5% weight change); propose constraint if violated	monthly_cvar_analysis.ipynb	[Name]	[Date]		No optimization rerun needed
Final Report	Cleanly formatted PDF report with insights, charts, and recommendation for your boss	Assignment_Portfolio_CVaR.ipynb	[Name]	[Date]		Use nbconvert or export from Colab
Generalization Check	All code runs on any valid dataset; avoids hard-coded tickers or values	All Notebooks	[Name]	[Date]		pd.read_csv block is clearly marked ✅
