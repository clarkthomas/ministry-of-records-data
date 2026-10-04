# Data files: FARA #7745, Sniper Advertising Services

CSV files of every principal and document the registrant's DOJ FARA eFile filings print, used in the research pack for FARA #7745. Exported 2026-10-04 from filings in the DOJ bulk index dated 10/04/2026.

| File | Rows | What it holds |
|---|---|---|
| principals.csv | 1 | The foreign principal, as printed. |
| documents.csv | 5 | The five eFile documents, with received date, page count and URL. |

**Rules**

- One row per printed item, copied as printed (spelling included). Dates are as printed.
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`).
- The registrant has filed no receipts, disbursements, activity contacts, printed totals or political contributions, so those files are not included. The short-form "Commission at 100,000.C % of 15" line is not a dollar figure and is not exported as one.
- No residence addresses, street addresses or birth years.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack are not included.

Ministry of Records is a records-only research desk.
