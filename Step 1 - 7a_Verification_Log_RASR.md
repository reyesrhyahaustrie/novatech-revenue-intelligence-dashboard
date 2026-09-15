# NovaTech Data Verification Log

**Student Name:** Rhyah Austrie S. Reyes
&nbsp;
**Date:** September 15, 2026

## Instructions
 
Query each pre-indexed knowledge base using Quick Chat. For each question, record the expected answer (from the data dictionary), Q's actual response, and whether they match. Minimum 6 entries (2 per data knowledge base).

## Verification Log

| # | Knowledge Base | Question Asked | Expected Answer | Q's Actual Answer | Match? | Notes |
|---|----------------|---------------|-----------------|-------------------|--------|-------|
| 1 | NovaTech CRM Deals | How many records are in the CRM deals data? | 499 | The CRM deals dataset contains 499 records. | Yes | Matches data dictionary row count |
| 2 | NovaTech CRM Deals | How many deals were won? | 315 | Out of the 499 total deals, 315 deals were won. | Yes | Matches the data dictionary Won count |
| 3 | NovaTech Marketing Campaigns | How many records are in the marketing campaigns data? | 2,240 | The marketing campaigns dataset contains 2,240 total records. | Yes | Matches data dictionary row count |
| 4 | NovaTech Marketing Campaigns | What is the response rate for campaigns? | 27.2% (609 of 2,240) | The overall campaign response rate is 27.19% — that's 609 responses out of 2,240 total records. | Yes | Matches data dictionary response rate |
| 5 | NovaTech Support Tickets | How many records are in the support tickets data? | 3,000 | The support tickets dataset contains 3,000 records. | Yes | Matches data dictionary row count |
| 6 | NovaTech Support Tickets | How many tickets are critical priority? | 50 | There are 50 tickets with critical priority in the support tickets dataset. | Yes | Matches data dictionary critical- priority count |

## Cross-Check

- **Fact verified:** How many records are in the CRM deals data?  
- **Chat said:** The CRM deals dataset contains 499 records.  
- **QuickSight shows:** The crm\_deals\_raw dataset (uploaded copy), where the refresh summary confirms that 499 rows were imported (100% success), which matched the pre-indexed knowledge base.
- **Consistent?** Yes, the pre-indexed knowledge base and the independently uploaded raw dataset agree on the row count, which confirms the source data was indexed accurately.
