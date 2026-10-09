# Risk Assessment and Portfolio Management

This repository contains a comprehensive analysis of portfolio management and risk assessment based on a hypothetical USD 20 million mandate. The project utilizes Modern Portfolio Theory (MPT), Value-at-Risk (VaR) measurements, corporate bond credit risk evaluation, and the design of an Investment Policy Statement (IPS).

## Repository Contents

*   **`Portfolio Management and Risk Analysis- Bikkumalla anish.docx`**: The primary research report detailing the methodology, rationale, and findings of the portfolio and risk analysis.
*   **`Bikkumalla anish.xlsx`**: The companion Excel workbook containing the complete working formulas, historical market data (January 2021 to June 2026), and quantitative models used to generate the report's calculations.

## Project Overview

### 1. Portfolio Construction and Optimization
The project constructs a diversified multi-asset portfolio using four Exchange-Traded Funds (ETFs) to capture different market regimes:
*   **VTI** (Vanguard Total Stock Market ETF) for US equity growth.
*   **EFA** (iShares MSCI EAFE ETF) for ex-US developed markets equity.
*   **VNQ** (Vanguard Real Estate ETF) for real estate exposure.
*   **AGG** (iShares Core U.S. Aggregate Bond ETF) for defensive fixed-income.

**Key Outcomes:**
*   The optimization targeted the Maximum Sharpe Ratio, bounded by a 5% minimum allocation per asset to enforce diversification.
*   **Optimal Allocation:** 60% VTI, 30% EFA, 5% VNQ, 5% AGG.
*   **Performance Metrics:** Projected annual yield of 12.32%, volatility of 15.33%, and a Sharpe Ratio of 0.559.

### 2. Market Risk Measurement (VaR)
The market risk of the optimized portfolio is evaluated using three distinct 1-day Value-at-Risk (VaR) methodologies to highlight differences in tail-risk estimation:
*   **Normal (Parametric) VaR:** Estimated at $307,962 (95%) and $439,610 (99%).
*   **Historical Simulation VaR:** Estimated at $293,602 (95%) and $525,173 (99%). 
*   **Monte Carlo Simulation VaR:** Estimated at $312,173 (95%) and $444,402 (99%).

**Conclusion:** The Historical Simulation captured empirical fat tails and extreme stress events (such as the 2022 market drop), resulting in a significantly higher 99% VaR compared to the parametric models that assume normal distributions.

### 3. Firm-Level Credit Risk and Bond Sensitivity
An in-depth analysis of Microsoft Corporation's 3.50% Senior Notes maturing in 2035 (ISIN US594918BC73).
*   **Credit Profile:** Assessed as a high-quality AAA/Aaa rated issuer characterized by a low debt-to-equity ratio (~30%) and exceptionally strong interest coverage (54x).
*   **Interest Rate Sensitivity:** The bond features a Macaulay Duration of 7.38 years, a Modified Duration of 7.22 years, and a Convexity of 60.559. 
*   **Scenario Analysis:** An unanticipated 25 basis point (bp) cut in the Fed rate would increase the bond's estimated price by 1.82%, moving it from $93.675 to $95.384.

### 4. Strategic Investment Policy Statement (IPS)
The final section designs a tailored IPS for a specific private client profile: a 45-year-old senior marketing executive and single parent with a $1,000,000 annual income.
*   **Strategy:** Recommends a Core-Satellite asset allocation approach. The core leverages the optimized, low-cost index funds established in Section 1, while satellite sleeves allow for concentrated, actively managed ESG-thematic investments aligned with the client's UN Sustainable Development Goals commitment.
*   **Risk Management:** Highlights behavioral finance considerations, specifically addressing the client's potential loss aversion and overconfidence, mitigated through disciplined procedural rebalancing and formalized annual governance.

## Usage
To review the calculations, open `Bikkumalla anish.xlsx`. The workbook includes distinct tabs for historical price data, MPT Optimization (utilizing Solver-derived weights), VaR comparisons (Parametric, Historical, Monte Carlo), and Bond Analysis. The theoretical frameworks and strategic conclusions are thoroughly documented in the accompanying Word file.
