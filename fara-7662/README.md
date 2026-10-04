# Data files: FARA #7662, Davis Media NY LLC

CSV files of every dollar figure, principal and document the registrant's DOJ FARA eFile filings print, used in the research pack for FARA #7662. Exported 2026-10-04 from filings in the DOJ bulk index dated 10/04/2026.

| File | Rows | What it holds |
|---|---|---|
| planned.csv | 4 | The Havas order figure, the L.D.R.S monthly rate and the two short-form fees, as printed. These are agreed or stated figures, not payments. |
| principals.csv | 2 | The two foreign principals, as printed. |
| documents.csv | 6 | The six eFile documents, with received date, page count and URL. |

**Rules**

- One row per printed item, copied as printed (spelling included). Dates are as printed.
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`).
- `amount_printed` is the text on the page. `amount_value` repeats it as a plain number for sorting. Nothing is summed.
- The registrant has filed no receipts, disbursements, activity contacts, printed totals or political contributions, so those files are not included.
- No residence addresses, street addresses or birth years.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack are not included.

Ministry of Records is a records-only research desk.
