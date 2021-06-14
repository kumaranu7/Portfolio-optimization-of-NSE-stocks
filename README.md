# Portfolio-optimization-of-NSE-stocks

- Pulled data from https://www1.nseindia.com/products/content/equities/equities/eq_security.htm , one can pull using api too.
- Analysed the data, its log return, checked for type of distribution, skewness and kutosis.
- Found out optimal weights to be assigned to each of the equity in the portfolio using different methods such as
      - Random weight intialization
      - Looping across random weights and finding the optimal weights by hit and trail
      - Using SciPy minimize solver and used 'SQSLP' solver
- Plotted return vs volatility and found out efficient frontier, also the best combination of weights against the given volatility.
