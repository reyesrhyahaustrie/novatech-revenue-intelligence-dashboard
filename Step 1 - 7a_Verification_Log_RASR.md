**NovaTech Data Verification Log**

*Rhyah Austrie S. Reyes (RASR)*

This queries each pre-indexed knowledge base using Quick Chat and compares each answer against the expected value from the Data Dictionary, Q's actual response, and whether they match. 6 entries, with 2 per data knowledge base.

| \# | Data Set | Question Asked | Expected Answer | Q's Actual Answer | Match? | Notes |
| :---- | :---: | :---: | :---: | :---: | :---: | :---: |
| **1** | **NovaTech CRM Deals** | How many records are in the CRM deals data? | 499 | &nbsp;The CRM deals dataset contains 499 records.&nbsp; | Yes | Matches data dictionary row count |
| **2** | **NovaTech CRM Deals** | How many deals were won? | 315 | &nbsp;Out of the 499 total deals, 315 deals were won.&nbsp; | Yes | Matches the data dictionary Won count |
| **3** | **NovaTech Marketing Campaigns** | How many records are in the marketing campaigns data? | 2,240 | &nbsp;The marketing campaigns dataset contains 2,240 total records.&nbsp; | Yes | Matches data dictionary row count |
| **4** | **NovaTech Marketing Campaigns** | What is the response rate for campaigns? | 27.2% (609 of 2,240) | &nbsp;The overall campaign response rate is 27.19% — that's 609 responses out of 2,240 total records.&nbsp; | Yes | Matches data dictionary response rate |
| **5** | **NovaTech Support Tickets** | &nbsp;How many records are in the support tickets data?&nbsp; | 3,000 | The support tickets dataset contains 3,000 records. | Yes | Matches data dictionary row count |
| **6** | **NovaTech Support Tickets** | &nbsp;How many tickets are critical priority?&nbsp; | 50 | &nbsp;There are 50 tickets with critical priority in the support tickets dataset.&nbsp; | Yes | Matches data dictionary critical- priority count |

&nbsp;

**Cross-Check**

* **Fact verified:** How many records are in the CRM deals data?  
* **Chat said:** The CRM deals dataset contains 499 records.  
* **QuickSight shows:** The crm\_deals\_raw dataset (uploaded copy), where the refresh summary confirms that 499 rows were imported (100% success), which matched the pre-indexed knowledge base.  
* **Consistent?** Yes, the pre-indexed knowledge base and the independently uploaded raw dataset agree on the row count, which confirms the source data was indexed accurately.
