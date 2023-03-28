#Path-Dependent-Options---Lookback-Call-Options-with-Stochastic-Volatility

Value a call option discretely monitored with stochastic volatility. Payoff depends on the extremum values of the price of the underlying asset over a certain period of time (lookback period). Two standard lookback options: fixed strike and floating strike. A fixed-strike discrete option pays the difference (if positive) between the maximum or minimum of a set of observations, during the asset price review period and the strike price on the expiration date . No analytical solution for the price of European fixed-exercise lookback call options with fixings and stochastic volatility according to the Heston model.But simple analytical formula for the price of a fixed strike lookback call continuously monitored with constant volatility. We will use a combination of Monte Carlo variance reduction techniques, such as antithetic and control variates, to reduce the standard error of our simulation. We use the continuously supervised fixed payback call option's analytical solution to calculate control variates based on delta, gamma and vega sensitivities.

Heston Model for Stochastic Volatility.

Analytical Solution for Continuous Observations.

General Control Variate Equation.

Implementation of Delta-based Control Variates using Least-Squares Regression to find the relationship between control variate hedges and payoff.

Gamma Based Control Variate.

Antithetic and control Variate and Comparing Variance Reduction Methods
