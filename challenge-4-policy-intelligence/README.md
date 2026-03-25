# Challenge 4: Policy intelligence at scale

**The question:** How can structured company data, combined with other public datasets, support better policy decisions at scale?

## Files included

| File | Description |
|------|-------------|
| `Accounts_Bulk_Data-2025-12-25.csv` | Companies House accounts bulk data (~39k rows). Foundation dataset with company financials and identifiers. |
| `UK_gender_pay_gap_data_2024_to_2025.csv` | Full UK Gender Pay Gap data 2024-25 (~16.5k employers). Linkable by company number. |
| `charity_commission_register_sample.tsv` | 2,000-row sample from the Charity Commission register. Linkable by charity number. |
| `BoE_Bankstats_TableA8.1_SME_lending.xls` | Bank of England Table A8.1: monthly SME lending volumes, repayments, and overdraft balances. |

## Additional data sources

| Dataset | URL |
|---------|-----|
| Charity Commission Register (full) | https://register-of-charities.charitycommission.gov.uk |
| ONS Labour Market Statistics | https://geoportal.statistics.gov.uk |
| NOMIS Local Area Data | https://nomisweb.co.uk |
| Insolvency Statistics | https://gov.uk/government/collections/insolvency-statistics |
| DSIT Innovation Clusters Map | https://innovationclusters.dsit.gov.uk |
| Innovate UK Funded Projects | https://ukri.org/what-we-do/what-we-have-funded/innovate-uk |
| Supplier Payment Practice Reports | https://check-payment-practices.service.gov.uk |
| LEI Data (GLEIF) | https://gleif.org/en/lei-data/access-and-use-lei-data |
| data.gov.uk | https://data.gov.uk |
| Companies House Bulk Company Data | https://download.companieshouse.gov.uk/en_output.html |
| UK Finance Postcode Lending Data | https://ukfinance.org.uk/data-and-research |

## Getting started ideas

1. Choose a policy question (e.g. early warning of financial stress in a sector, tracking grant recipients).
2. Use the XBRL to CSV Converter to extract structured financials for a cluster of companies (by SIC code or postcode).
3. Link with the included Gender Pay Gap, Charity Commission, or Bank of England data.
4. Map out what a policy dashboard would need and what data connections are missing.
