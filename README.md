# Blue-Owl-Capital-3-Statment-Model
### 3-statement financial model for Blue Owl Capital, built from imported SEC EDGAR data using Power Query and Excel
This project extracts live SEC filing data via the XBRL API, transforms it with Power Query, and builds a linked Income Statement, Balance Sheet, and Cash Flow Statement in Excel.
#### Key Componets:
Automated Data Pipeline: Power Query pulls financials directly from SEC EDGAR's JSON API (CIK 0001823945), eliminating manual data entry
Historical Analysis (2019–2025): 7 years of audited 10-K data with GAAP-tagged line items
Forecasting Framework: Assumption-driven projections through 2030 with data pulled from 2026 Q1 investor decks, including revenue growth, compensation ratios, and tax rates
Credit & Profitability Ratios: Leverage, coverage, liquidity, and per-share metrics
Balance Sheet Check: Automatic validation that Assets = Liabilities + Equity
Cash Flow Reconciliation: Links net income to operating cash flow with non-cash adjustments
Tools Used:
Excel, Power Query (M language), SEC EDGAR XBRL API

Skills:
Financial statement analysis, data extraction & transformation, formula-based modeling, assumption-driven forecasting, ratio analysis
