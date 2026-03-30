# Marketing-Mix-Modeling-VAR-Analysis
Econometric analysis using Vector Autoregression (VAR) to quantify the dynamic impact of pricing and advertising on sales volume in the organic food sector.

Project Overview
This project investigates how internal marketing levers (Price and Advertising) and external competitor actions dynamically influence sales performance. Using a time-series dataset from the organic food sector, the study applies advanced econometric modeling to quantify market sensitivity, brand loyalty, and the duration of marketing effects over a quarterly horizon.
🛠️ Methodological Workflow
The analysis follows a rigorous data science pipeline implemented in R:
Stationarity & Unit Root Testing: Verified time-series stability using Augmented Dickey-Fuller (ADF), Phillips-Perron (PP), and KPSS tests to ensure robust model estimation.
Causal Inference: Conducted Granger Causality tests to identify temporal relationships and lead-lag effects between variables.
VAR Modeling: Estimated a Vector Autoregression (VAR) system to account for simultaneous feedback loops in the market.
Dynamic Analysis:
Impulse Response Functions (IRF): To simulate the net effect of market shocks over time.
Forecast Error Variance Decomposition (FEVD): To determine the relative importance of each variable in driving sales volatility.
📈 Key Findings
Price Sensitivity: Own price emerged as a dominant driver with a significant negative impact on volume (Short-term elasticity: -1.39).
Marketing Decay: The impact of advertising activities is short-lived, with effects typically decaying completely within a 5-week window.
Market Inertia: A strong "habit effect" was identified, where past sales significantly influence current performance, indicating high consumer loyalty.
Competitive Resilience: The analysis revealed high immunity to competitor pricing and advertising shocks during the period studied.
💡 Strategic Recommendations
Optimize Pricing: Prioritize pricing strategy as the primary tactical lever, as consumers react instantly to price changes.
Ad Spend Efficiency: Re-evaluate intermittent "burst" advertising strategies due to their rapid decay and marginal long-term impact.
Retention Focus: Invest in maintaining sales momentum and customer loyalty, which serve as a natural buffer against market volatility.
💻 Tech Stack
Language: R
Key Libraries: vars, lmtest, aTSA, RColorBrewer, gplots

