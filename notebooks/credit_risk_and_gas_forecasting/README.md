# Quantitative Analysis: Credit and Commodities
These two projects come from JPMorgan quantitative training program (forage). The credit default analysis focuses on assessing borrower risk and predicting loan defaults, while the gas storage valuation addresses pricing and cash flow evaluation for energy contracts. These are real challenges JPMorgan faces across different divisions. The solutions here are my own implementations developed as part of their quantitative trading program, reflecting practical approaches to complex financial problems.

## Projects:

**[Credit Default Analysis](Credit_default_regression_and_binning.ipynb)**

Performs logistic regression to predict loan defaults using FICO scores and other factors. It calculates optimal FICO score bins with minimum data sizes and visualizes default rates by score ranges to better understand credit risk.

**[Gas Storage Contract Valuation](Nat_Gas_Price_Forcasting.ipynb)**

Calculates the net present value (NPV) of a gas storage contract based on injection and withdrawal schedules. It simulates daily storage levels, accounts for maximum capacity and monthly storage costs, and uses historical gas prices to value cash flows. This provides a realistic financial assessment of the contract’s profitability.

Both scripts are designed for clarity and easy adaptation to similar datasets, aiding decision making in credit risk and energy contract valuation.
