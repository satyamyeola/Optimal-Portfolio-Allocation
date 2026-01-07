# Optimal-Portfolio-Allocation
In this project the main aim is to find the best combination of proportion of the part of my capital i can invest in the assets so that i can get maximum return with a minimum risk.
# KEY CONCEPTS
* Data Processing : Fetched 3 years of adjusted closing prices using yfinance.
* Statistical Part : Calculated the Annualized Mean Return (μ) and the Annualized Covariance Matrix (Σ).
* Risk Measurement: Established that risk is mathematically defined by the variance and covariance of asset returns.
* The Minimum Variance Portfolio (MVP): Identified the absolute "left-most" point on the risk-return graph.
* Risk-Return Trade-off (Formulation B) : Constructed an objective function to Maximize: Return - λ*Risk ,λ controls risk         aversion.
* Used CVXPY to solve the convex optimization problem.
* Tracing the Efficient Frontier :Demonstrated that any portfolio below this line is preferred because one
  could achieve a higher return for the same risk by moving vertically to the frontier or for can a given return one could        achive minimum risk by going to the leftmost point on the frontier plot.
