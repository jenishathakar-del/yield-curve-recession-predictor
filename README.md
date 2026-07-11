# yield-curve-recession-predictor
# Sovereign Yield Curve Inversion & Macroeconomic Recession Predictor

## Academic Overview
This project constructs a predictive econometric forecasting engine that monitors sovereign debt market spreads. By analyzing the yield differential between short-term and long-term government bonds (the 10-2 spread), the framework evaluates boundary conditions to algorithmically calculate systemic recession probabilities and output strategic asset reallocation directives for institutional portfolios.

## The Economic & Philosophical Thesis
In stable macroeconomic environments, the yield curve slopes upward, reflecting a term premium for locked capital. However, when market participants anticipate near-term systemic contraction, demand shifts aggressively toward long-term liquid instruments, depressing long-term yields while short-term rates spike under liquidity strains. 

This project explores the yield curve inversion as a highly reliable leading indicator of market cycle transition. The framework proves how tracking structural distortions in fixed-income instruments allows quantitative macro-analysts to forecast contractionary macroeconomic shocks long before they manifest in backward-looking equity market data or GDP reports.

## Quantitative Methodology
The engine assesses market health by tracking the spread delta Y between the 10-Year Bond Yield and the 2-Year Bond Yield:

$$\Delta Y = Y_{10} - Y_{2}$$

The systemic risk profile is evaluated through a deterministic conditional probability function:

$$P(\text{Recession}) = \begin{cases} 92.5\% & \text{if } \Delta Y < 0 \\ 12.0\% & \text{if } \Delta Y \ge 0 \end{cases}$$

Where a negative spread represents a structural inversion boundary breach, triggering an automated capital reallocation script to shift mock institutional assets out of highly cyclical equities and into defensive, interest-bearing capital reserves.

## Empirical Results & Conclusion
* **2-Year Sovereign Bond Yield:** 4.85%
* **10-Year Sovereign Bond Yield:** 4.21%
* **Calculated 10-2 Yield Spread:** -0.64% (Breached Inversion Boundary)
* **Algorithmic Recession Forecast:** 92.5% Probability Within 12 Months
* **Portfolio Directives:** Cyclical Risk-Off Protocols Enforced

## Strategic Macro-Finance Conclusion
The forecasting model provides a clear empirical framework for structural risk management. By showing how a simple fixed-income spread can be programmatically mapped to institutional portfolio directives, this project underscores the vital intersection between sovereign bond market microstructure and macroeconomic risk arbitrage within global banking systems.
