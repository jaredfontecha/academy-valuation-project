# Academy Sports + Outdoors Valuation

Private equity-style financial modeling and valuation project for **Academy Sports + Outdoors (NASDAQ: ASO)**.

The project builds a fully integrated financial model using Academy's public filings and market data, then values the company using **DCF, trading comparables, and leveraged buyout analysis**.

## Project Overview

The goal of this project was to develop a complete valuation model from the ground up and practice the core modeling techniques used in investment banking, private equity, and corporate finance.

The workbook includes:

* Historical financial statement analysis
* Operating forecast
* Integrated 3-statement model
* Discounted Cash Flow valuation
* Trading comparable companies analysis
* Leveraged Buyout analysis
* DCF and LBO sensitivity analyses
* Automated model integrity checks
* Source documentation

## Company

**Academy Sports + Outdoors, Inc.**
Ticker: **ASO**

Academy is a U.S. sporting goods and outdoor recreation retailer.

Historical financial data was primarily sourced from Academy's SEC filings and company earnings materials.

## Model Structure

The Excel workbook contains the following tabs:

### Cover

Model title and project information.

### Sources

Tracks the filings, market data, and other sources used throughout the model.

### Historicals

Historical income statement, balance sheet, and cash flow statement data.

### Assumptions

Forecast drivers including revenue growth, margins, working capital, CapEx, depreciation, taxes, and other operating assumptions.

### Operating Model

Forecasts revenue, gross profit, SG&A, operating income, and operating margins through FY2030E.

### 3-Statement

Integrated forecast linking the income statement, balance sheet, and cash flow statement.

The model includes balance sheet and cash flow checks to ensure the statements remain internally consistent.

### DCF

Discounted Cash Flow valuation based on projected unlevered free cash flow.

Key inputs include:

* Risk-free rate
* Equity risk premium
* Levered beta
* Cost of equity
* Cost of debt
* Capital structure
* WACC
* Terminal growth rate

The DCF also includes a two-variable sensitivity analysis for WACC and terminal growth.

### Comps

Trading comparable company analysis using:

* DICK'S Sporting Goods
* Boot Barn
* Sportsman's Warehouse
* Tractor Supply Company

Valuation multiples include:

* EV / Revenue
* EV / EBITDA
* P / E

The analysis uses median peer multiples to calculate implied Academy share prices.

### LBO

Simplified private equity leveraged buyout model.

The LBO includes:

* Acquisition premium
* Sources & uses
* Entry leverage
* Sponsor equity contribution
* Operating cash generation
* LBO-specific cash taxes
* Interest expense
* Debt paydown
* Exit valuation
* MOIC
* IRR
* Entry leverage / exit multiple sensitivity analysis

### Checks

Automated checks for:

* Balance sheet balance
* Cash flow reconciliation
* LBO sources and uses
* Negative debt
* Sponsor equity
* Base-case LBO sensitivity consistency

## Selected Valuation Outputs

### DCF

Base-case implied share price:

**$102.96**

### Trading Comparables

Implied share price range:

**$66.42 – $101.61**

Average implied share price:

**$86.81**

### LBO Base Case

Key assumptions:

* 20.0% acquisition premium
* 4.50x entry Debt / EBITDA
* 4.50x exit EV / EBITDA
* 7.5% cash interest rate
* 5-year holding period
* $100 million minimum cash balance

Base-case sponsor returns:

**MOIC: 2.82x**

**IRR: 23.1%**

## Data Sources

Primary sources include:

* Academy Sports + Outdoors SEC filings
* Academy earnings releases
* U.S. Treasury
* NYU Stern / Aswath Damodaran
* Public market data
* Comparable-company SEC filings and earnings materials

The model generally uses each comparable company's latest completed fiscal-year financials as a proxy for LTM results due to project scope and data availability.

Market values are based on market data collected as of **August 26, 2026**.

## Repository Structure

```text
academy-valuation-project/
├── data/
│   └── raw/
│       ├── Academy SEC filings
│       ├── earnings releases
│       └── comparable-company source documents
├── models/
│   └── academy_financial_model.xlsx
├── presentation/
│   └── academy_valuation_pe_pitch_deck.pptx
└── README.md
```

## Tools Used

* Microsoft Excel
* SEC EDGAR
* Git
* GitHub
* VS Code

## Skills Demonstrated

* Financial statement analysis
* Financial modeling
* Forecasting
* 3-statement modeling
* DCF valuation
* Comparable-company analysis
* LBO modeling
* Sensitivity analysis
* Excel modeling conventions
* Financial data sourcing
* Model auditing and integrity checks
* Git / GitHub version control

## Disclaimer

This project was created for educational and portfolio purposes only. It is not investment advice and should not be interpreted as a recommendation to buy or sell Academy Sports + Outdoors securities.
