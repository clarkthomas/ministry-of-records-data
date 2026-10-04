# Data files: FARA #7641, Rabinowitz, Inc. d/b/a Bluelight Strategies

CSV files of every row the registrant's DOJ FARA eFile filings print, used in the research pack for FARA #7641. Exported 2026-10-03 from filings pulled 2026-10-03.

| File | Rows | What it holds |
|---|---|---|
| receipts.csv | 1 | The registration's one receipt row (also printed in Exhibit B Item 12). |
| disbursements.csv | 0 | No disbursement row is printed (header only). |
| contacts.csv | 0 | No contact row is printed (header only). |
| principals.csv | 1 | The foreign principal as printed. |
| printed_totals.csv | 2 | Each total as the filings print it. |
| contributions.csv | 0 | No contribution row is printed (header only). |

**Rules**

- One row per printed item, copied as printed (spelling included).
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`). Some rows cite more than one page where several filings print the same item.
- `amount_printed` is the text on the page. `amount_value` repeats it as a plain number for sorting. Nothing is summed; printed totals are in `printed_totals.csv`.
- No residence addresses or birth years.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack are not included.

Ministry of Records is a records-only research desk.
