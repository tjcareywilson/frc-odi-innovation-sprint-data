# Challenge 3: AI optimisation — how can we optimise structured data for AI?

**The question:** What changes to structure, metadata, access and governance would meaningfully improve how AI systems use company reporting data?

## Files included

| File | Description |
|------|-------------|
| `CoHo_random_50_filings_data_CLEAN.xlsx` | Random sample of 50 Companies House filings with XBRL tag-level data (~11.3k rows). Use to test how AI interprets structured reporting data and where it fails. |

## Key tools and data sources

| Resource | URL |
|----------|-----|
| MLCommons Croissant | https://github.com/mlcommons/croissant |
| ODI AI-ready data framework | https://theodi.org |
| UK iXBRL Viewer | https://ukixbrlviewer.org.uk |
| XBRL to CSV Converter | https://xbrl-to-csv.streamlit.app |
| Companies House API | https://developer.company-information.service.gov.uk |
| Companies House Bulk Accounts Data | https://download.companieshouse.gov.uk/en_accountsdata.html |
| FCA National Storage Mechanism | https://data.fca.org.uk/#/nsm/nationalstoragemechanism |
| filings.xbrl.org API | https://filings.xbrl.org/docs/api |
| Arelle | https://arelle.org |
| Fandascope | https://fandascope.com |

## Getting started ideas

1. Upload the included XBRL data (or a CSV from the XBRL to CSV Converter) into a conversational AI tool.
2. Ask it to summarise or interpret the data. Note where it misinterprets periods, definitions, scale, or context.
3. Compare the AI's interpretation against what you see in the UK iXBRL Viewer.
4. Identify what additional context or metadata would have prevented those errors.
5. Design a checklist, metadata template, or roadmap showing what changes would make AI outputs safer and more reliable.
