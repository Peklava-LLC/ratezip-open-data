# RateZip Open Consumer Finance Datasets (2026–2027)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Clean, reproducible CSV datasets published by **[RateZip](https://www.ratezip.com/)** (Peklava LLC, DBA RateZip · NMLS #1592292) for journalists, economists, researchers, and AI agents.

- **Methodology:** https://www.ratezip.com/methodology
- **Live MCP Server (zero auth, read-only):** `https://mcp.ratezip.com/mcp`
- **Capabilities JSON:** https://mcp.ratezip.com/quote-service/v1/capabilities
- **Open Rates API & Free Newsroom Widgets:** https://www.ratezip.com/open-rates
- **Hugging Face Datasets:** https://huggingface.co/datasets/peklava/ratezip-us-consumer-finance-2026
- **Kaggle Datasets:** https://www.kaggle.com/datasets/paulknag/ratezip-u-s-consumer-finance-open-datasets-2026
- **Glama Verified MCP Connector (`com.ratezip/rates`):** https://glama.ai/mcp/connectors/com.ratezip/rates

---

## Included Datasets

### 1. 50-State CD vs. 1-Year Treasury Tax Hurdle (`savings-gap-50-states.csv`)
- **Canonical study & live tracker:** https://www.ratezip.com/data/savings-gap
- **What's inside:** All 50 U.S. states + Washington, D.C., ranked by the taxable bank CD APY required to match a state-tax-exempt 1-year U.S. Treasury yield after 2026 marginal state income taxes (top and common brackets). Paired with daily tracking of standard savings rates at Chase (0.01%), Wells Fargo (0.01%), and Bank of America (0.04%) vs. top online savings accounts.

### 2. 10-Jurisdiction Official `.gov` Auto Insurance Quote Audit (`state-doi-auto-study.csv`, `state-doi-auto-summary.csv`)
- **Canonical study & interactive charts:** https://www.ratezip.com/data/auto-insurance-study
- **What's inside:** **53,685 official quotes** collected directly from 10 state department of insurance rate comparison databases (CA, TX, NY, FL, NJ, MD, DC, KY, AL, WV), showing 3.2x to 12.1x price spreads for identical driver profiles across carriers.

### 3. 126-City 2027 Mortgage Readiness & Post-2021 Home Equity Study (`mortgage-readiness-cities-2027.csv`)
- **Canonical study & searchable table:** https://www.ratezip.com/data/mortgage-readiness-cities-2027
- **What's inside:** 126 U.S. cities ranked by post-2021 homebuyer equity resilience, underwater share percentages, median home-value gains since purchase, and credit-readiness indicators.

---

## Citation & Attribution (CC-BY-4.0)

You are free to share, analyze, visualize, and build on these datasets with attribution:

> Source: RateZip (https://www.ratezip.com/data/savings-gap | https://www.ratezip.com/data/auto-insurance-study | https://www.ratezip.com/data/mortgage-readiness-cities-2027), CC-BY-4.0.

Media or data inquiries: `press@ratezip.com`
