# Monte Carlo Engine -- Probability & Simulation

## Objective

In this lab, I used Monte Carlo simulation to study probability, Bayes' Theorem, and financial risk.

## Methodology

- Simulated 10,000 fair coin flips and tracked how the running proportion of heads converged toward 0.5.
- Simulated 10,000 Monty Hall games and compared the strategies of staying versus switching.
- Simulated a disease screening test on 100,000 people using a 1% prevalence rate, 95% sensitivity, and 90% specificity.
- Used Bayes' Theorem to compare the analytical probability of being sick after a positive test with the simulation result.
- Simulated 10,000 daily portfolio returns for a $1,000,000 portfolio.
- Calculated 95% and 99% Value at Risk (VaR) and Expected Shortfall (ES).
- Used an AI-generated `var_es` function and checked its results against my own calculations.

## Key Findings

- In the Monty Hall simulation, switching won 6,694 out of 10,000 games, which was close to the theoretical probability of two-thirds.
- In the disease screening simulation, about 9.2% of people who tested positive were actually sick.
- The 95% VaR for the $1,000,000 portfolio was $19,494.
- The 95% Expected Shortfall was $24,230.
- The 99% VaR was $27,046, and the 99% Expected Shortfall was $31,221.
- Expected Shortfall was larger than VaR because it measures the average loss during the worst tail outcomes rather than only the loss cutoff.
