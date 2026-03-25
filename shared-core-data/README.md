# Shared Core Data

Datasets relevant to all four challenges.

## Files included

### Accounts_Bulk_Data-2025-12-25.csv
Companies House accounts bulk data snapshot (25 Dec 2025). Contains ~39,000 rows of structured financial data extracted from iXBRL filings, including balance sheet items, profit and loss, company identifiers, SIC codes, and charity status.

**Key columns:** company_id, entity_current_legal_name, tangible_fixed_assets, current_assets, net_assets, turnover, profit_loss, SIC codes, charity fields.

**Source:** https://download.companieshouse.gov.uk/en_accountsdata.html

### CoHo_random_50_filings_data_CLEAN.xlsx
A random sample of 50 Companies House filings with detailed XBRL tag-level data (~11,300 rows). Each row represents an individual tagged data point from a filing, including the XBRL concept, label, numeric and text values, dimensional breakdowns, and a link to the UK iXBRL Viewer.

**Key columns:** Company, CRN, Filing, Concept, Label, Value_numeric, Value_text, Period_start, Period_end, Viewer_link, plus ~60 dimension columns.

**Source:** Extracted via stream-read-xbrl from Companies House bulk accounts data.
