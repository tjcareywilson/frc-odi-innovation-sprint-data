# FRC & ODI Open Structured Company Data Innovation Sprint

Sample datasets and resources for the sprint, organised by working group (challenge). Each folder contains pre-downloaded data relevant to that challenge, plus links to additional sources.

## Folder structure

```
shared-core-data/              Datasets used across all challenges
challenge-1-sme-finance/       Challenge 1: Structured data for SME finance and investment
challenge-2-trust-in-tags/     Challenge 2: Trust in the Tags
challenge-3-ai-optimisation/   Challenge 3: AI optimisation for structured data
challenge-4-policy-intelligence/ Challenge 4: Policy intelligence at scale
```

## Shared core tools (all challenges)

| Resource | URL |
|----------|-----|
| Companies House Bulk Company Data | https://download.companieshouse.gov.uk/en_output.html |
| Companies House Bulk Accounts Data | https://download.companieshouse.gov.uk/en_accountsdata.html |
| Companies House API (free key required) | https://developer.company-information.service.gov.uk |
| UK iXBRL Viewer | https://ukixbrlviewer.org.uk |
| XBRL to CSV Converter | https://xbrl-to-csv.streamlit.app |
| DBT stream-read-xbrl (Python) | https://pypi.org/project/stream-read-xbrl |
| Companies House URI Service | http://data.companieshouse.gov.uk/doc/company/{companynumber} |

## Pre-downloaded datasets included

| File | Description | Challenges |
|------|-------------|------------|
| `Accounts_Bulk_Data-2025-12-25.csv` | Companies House accounts bulk data (~39k rows) | All |
| `CoHo_random_50_filings_data_CLEAN.xlsx` | Sample of 50 CoHo filings with XBRL tag-level data (~11k rows) | All |
| `UK_gender_pay_gap_data_2024_to_2025.csv` | UK Gender Pay Gap data 2024-25 (~16.5k employers) | 1, 4 |
| `charity_commission_register_sample.tsv` | 2,000-row sample from the Charity Commission register | 1, 4 |
| `BoE_Bankstats_TableA8.1_SME_lending.xls` | Bank of England Table A8.1 — monthly SME lending | 1, 4 |

## Getting started

1. Register for a free Companies House API key at https://developer.company-information.service.gov.uk
2. Browse the data in the folder for your challenge.
3. See the README inside each challenge folder for challenge-specific guidance and additional data sources.
