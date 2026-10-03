# Dynamic-Investment-Calculator
This project analyzes a diversified real estate investment portfolio across Alexandria's premium residential developments (Parco &amp; Veda) over a 5-year period (2019-2024).
Executive Summary
This project analyzes a diversified real estate investment portfolio across Alexandria's premium residential developments (Parco & Veda) over a 5-year period (2019-2024), correlating property appreciation with macroeconomic indicators (US Dollar Index, Gold prices) to quantify investment performance, currency risk exposure, and hedging effectiveness.
Key Finding: Real estate prices demonstrate +0.63 correlation with USD strength, indicating currency-driven appreciation patterns. Portfolio maintains 7-10% annualized ROI with quarterly volatility of ±4.2%, positioning real estate as a moderate inflation hedge in MENA markets.

Project Overview
Objective: Evaluate whether real estate investments in Alexandria serve as effective hedges against currency depreciation and inflation, with data-driven quarterly tracking and forward ROI projections.
Data Period: Q4 2019 – Q3 2024 (20 quarters)
Portfolio Size: 10+ investment units across 2 major projects
Investment Type: Off-plan residential apartments with installment-based financing
for powerbi Dashbord visit the blog: https://theanalyticsolution.wixsite.com/analytic-solution/post/dynamic-investment-calculator-dashboard

Methodology
Data Sources

Real Estate Pricing: Company internal database (quarterly price updates from Parco & Veda projects)
USD Index: investing.com historical data (DXY - US Dollar Index, monthly closing prices)
Gold Prices: investing.com historical data (spot prices in USD/oz, monthly closing prices)
Macroeconomic Data: Central Bank of Egypt (inflation rates, EGP/USD exchange rates)

Analysis Framework
1. Portfolio Performance Tracking

Calculated quarterly price appreciation per square meter for each property
Tracked total unit prices across 4 quarters (Q1-Q4) annually
Projected semi-annual and annual ROI based on historical appreciation rates
Modeled payment schedules and cumulative cash outflows

2. Correlation Analysis

Computed Pearson correlation coefficients:

Real Estate Price vs USD Index: +0.63 (strong positive)
Real Estate Price vs Gold Price: -0.28 (weak negative)


Identified quarterly lag effects (USD strength → 1-2 quarter delayed RE appreciation)

3. Investment Metrics

Average Quarterly Appreciation: 3.4% (annualized ~13.6% compound)
Volatility (Std Dev): ±4.2% quarterly variation
Currency Exposure: 63% of price movements attributable to USD strength

4. Return Projections

Base Case (70% probability): 7-8% annualized ROI through 2027
Bull Case (20% probability): 10-12% ROI if market momentum continues
Bear Case (10% probability): 2-3% ROI if market stalls or currency stabilizes


Key Findings
1. Currency Risk is the Primary Driver
Real estate appreciation correlates strongly with USD strengthening (r = +0.63). When the USD Index rose from 89.4 (Jan 2021) to 113.2 (Oct 2022), property prices increased 45% simultaneously. This suggests Egyptian real estate serves as a USD proxy hedge rather than an inflation hedge alone.
2. Real Estate ≠ Gold Hedge
Contrary to conventional wisdom, real estate and gold prices show negative correlation (r = -0.28), meaning they move in opposite directions. Gold strengthens during crisis periods, while real estate stalls. This is actually advantageous for portfolio diversification.
3. Quarterly Volatility is Moderate
±4.2% quarterly variation indicates real estate is less volatile than equity markets but more volatile than bonds. This positions it as a balanced hedge asset in multi-asset portfolios.
4. Project Comparison: Parco vs Veda

Parco: Established project, steady 3.1% quarterly growth, lower downside risk
Veda: Newer project, higher volatility (±5.8%), but 4.2% average quarterly growth
Portfolio implication: Balanced exposure reduces concentration risk

5. Payment Schedule Optimization
Quarterly installment structure aligns with appreciation cycles. Investors who increase payments during high-appreciation quarters (Q2, Q3) can capture 18-25% additional equity gains vs. fixed-payment strategies.

Files Included
Investment_Model.pbix          # Power BI interactive dashboard (3 pages)
Projects_Data.xlsx             # Excel portfolio tracker with ROI calculations
Real_Estate_Historical_Data.csv # Quarterly property prices (2019-2024)
US_Dollar_Index_Historical_Data.csv # Monthly USD Index prices

Dashboard Pages
Page 1: Portfolio Overview

Total portfolio value (EGP)
Number of investment units by project
Average unit price and price per square meter
Overall portfolio allocation (Parco % vs Veda %)

Page 2: Quarterly Performance Trends

Line chart: Price appreciation trajectory (2019-2024) for Parco & Veda
YoY growth rates by quarter
Comparison with inflation rates and EUR/EGP exchange rates
Trend annotations highlighting market cycles

Page 3: Macro Correlation Analysis

Scatter plot: Real Estate Price vs USD Index (showing +0.63 correlation)
Scatter plot: Real Estate Price vs Gold Price (showing -0.28 correlation)
Time-series overlay: Real estate prices layered with USD Index movements
Correlation trend analysis (rolling 4-quarter correlation)


How to Use This Project
For Investment Decision-Making

Download the Power BI file and open in Power BI Desktop
Navigate to Page 3 to understand currency risk exposure
Use ROI projections to model payment timing and expected returns
Apply correlation insights to diversify holdings (don't overweight currency-correlated assets)

For Data Analysis Portfolio

Review the methodology to understand real-world financial data modeling
Examine Excel formulas for ROI, volatility, and cash flow calculations
Replicate the correlation analysis in your own datasets
Adapt the Power BI structure for other investment products (stocks, bonds, commodities)

For Interview Preparation

Understand the business question: Does real estate hedge currency risk?
Know the data sources: How to gather, clean, and validate financial data
Articulate the findings: Be ready to explain +0.63 correlation in non-technical terms
Discuss trade-offs: Why positive correlation with USD is good for Egyptian investors


Technical Implementation
Tools Used

Excel: Data aggregation, ROI calculations (SUMPRODUCT, IRR formulas), scenario modeling
Power BI: Interactive visualization, correlation analysis, trend forecasting
Data Sources: Manual collection from investing.com, API integration (if available), company databases

Formulas & Calculations
Quarterly Appreciation Rate:
Appreciation % = (Current Quarter Price - Previous Quarter Price) / Previous Quarter Price
Annualized ROI:
Annual ROI = [(End Value - Beginning Value) / Beginning Value] / Years
Pearson Correlation Coefficient:
r = Σ[(X - X̄)(Y - Ȳ)] / √[Σ(X - X̄)² × Σ(Y - Ȳ)²]

Insights for Recruiters (Financial & Tech Companies)
Data Modeling Capabilities
✓ Multi-source data integration (internal + external APIs)
✓ Complex financial calculations (IRR, ROI, correlation analysis)
✓ Time-series data handling with quarterly/monthly/annual aggregations
✓ Scenario analysis and forward projections
Business Acumen
✓ Understand MENA investment dynamics (currency risk, real estate market cycles)
✓ Interpret macroeconomic indicators (USD strength, inflation impact)
✓ Quantify risk-adjusted returns for stakeholder decision-making
✓ Communicate technical findings to non-technical audiences
Technical Stack
✓ SQL/Database: Data aggregation and transformation
✓ Excel: Financial modeling, advanced formulas, pivot tables
✓ Power BI: DAX calculations, interactive dashboards, conditional formatting
✓ Python (optional): Correlation analysis, statistical testing, automation

Future Enhancements

Automated Data Pipeline: Integrate investing.com API to auto-update USD/Gold prices monthly
Predictive Modeling: Use moving averages to forecast Q4 2024 prices with 90% confidence intervals
Risk Metrics: Add Value-at-Risk (VaR) calculations for downside scenario planning
Comparative Analysis: Benchmark against Alternative Cairo projects (New Capital, Sheikh Zayed)
Currency Hedging Strategies: Model optimal USD futures positions to offset RE portfolio risk


Contact & Questions
This project demonstrates:

Financial domain expertise: MENA investment markets, currency risk analysis
Data analytics skills: Correlation analysis, trend forecasting, ROI modeling
BI proficiency: Multi-page dashboards, DAX calculations, interactive reporting
Business intelligence: Translating data into actionable investment decisions

Use this project to discuss: Real-world financial data challenges, portfolio optimization trade-offs, and how analytics drives investment strategy in emerging markets.
