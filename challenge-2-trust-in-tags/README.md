# Challenge 2: Trust in the Tags

**The question:** How can we design a transparent, user-focused way to assess and communicate tagging quality?

## Files included

| File | Description |
|------|-------------|
| `CoHo_random_50_filings_data_CLEAN.xlsx` | Random sample of 50 Companies House filings with detailed XBRL tag-level data (~11.3k rows). Use to examine tagging patterns, consistency, and quality. |

## Key tools and data sources

| Resource | URL |
|----------|-----|
| Arelle (open-source XBRL platform) | https://arelle.org |
| FRC Hackathon Arelle Streamlit app | https://hackathon-ihys2cq2rryh6ezdr6qbgr.streamlit.app/ |
| Xule (XBRL business rules processor) | https://github.com/xbrlus/xule |
| XBRL US Data Quality Committee Rules | https://xbrl.us/home/priorities/data-quality/rules-guidance |
| XBRL US Approved Validation Rules | https://xbrl.us/xbrl-taxonomy/approved-validation-rules |
| Fandascope | https://fandascope.com |
| XBRL Filing Index | https://filings.xbrl.org |
| XBRL Filing Quality Report | https://dapper-conkies-54c70a.netlify.app |
| MLCommons Croissant | https://github.com/mlcommons/croissant |
| Companies House Bulk Accounts Data | https://download.companieshouse.gov.uk/en_accountsdata.html |
| FCA/NSM (listed company filings) | https://data.fca.org.uk/#/nsm/nationalstoragemechanism |

## Getting started ideas

1. Use the included CoHo filings data to explore tagging patterns across 50 real filings.
2. Pick a few CRNs and view their filings in the UK iXBRL Viewer (https://ukixbrlviewer.org.uk).
3. Run filings through Arelle or the Streamlit app to see validation errors.
4. Use Fandascope to check for presentation inconsistencies.
