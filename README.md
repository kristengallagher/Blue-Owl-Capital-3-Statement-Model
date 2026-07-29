# Blue Owl Capital 3-Statement-Model
#### Full 3-statement financial model for Blue Owl Capital (NYSE: OWL), built from live SEC EDGAR data using Power Query and Excel.
This project extracts live SEC filing data via the XBRL API, transforms it with Power Query, and builds a linked Income Statement, Balance Sheet, and Cash Flow Statement, reconciled to the 10-K.

### Key Components:
- **Automated Data Pipeline** : Power Query pulls financials directly from SEC EDGAR's JSON API (CIK 0001823945), eliminating manual data entry
- **Historical Analysis (2019–2025)** : 7 years of audited 10-K data with GAAP-tagged line items
- **Forecasting Framework** : assumption-driven projections through 2030, informed by 2026 Q1 investor deck guidance on revenue growth, compensation ratios, and tax rates
- **Credit & Profitability Ratios** : leverage, coverage, liquidity, and per-share metrics
- **Balance Sheet Check** : automatic validation that Assets = Liabilities + Equity
- **Cash Flow Reconciliation** : links net income to operating cash flow with non-cash adjustments

### Tools Used:
- Excel
- Power Query (M language)
- SEC EDGAR XBRL API

#### Skills:
```python
- Financial statement analysis
- Data extraction & transformation
- Formula-based modeling
- Assumption-driven forecasting
- Ratio analysis
```

*For demonstration purposes only. Prepared independently by Kristen Gallagher.*

## License

© 2025 Kristen Gallagher. All rights reserved. This work is made available for viewing and reference purposes only. You may not reproduce, distribute, modify, or claim this work as your own without explicit written permission from the author.
