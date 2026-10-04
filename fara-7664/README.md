# Data files: FARA #7664, American Future Fund

CSV files of every row the registrant's DOJ FARA eFile filings print, used in the research pack for FARA #7664. Exported 2026-10-03 from filings pulled 2026-10-03.

| File | Rows | What it holds |
|---|---|---|
| receipts.csv | 1 | The supplemental's one receipt row. |
| disbursements.csv | 2 | The supplemental's two advertising rows (printed date range 11/01/2025-04/30/2026). |
| contacts.csv | 2 | Supplemental Item 12 entries. |
| principals.csv | 2 | The foreign principal, and the firm named in Exhibit B, as printed. |
| printed_totals.csv | 2 | Each total as the filings print it. |
| contributions.csv | 15 | Political contributions as reported to FARA (registration Item 10(c); supplemental Item 15(c)). |

**Rules**

- One row per printed item, copied as printed (spelling included). Dates are as printed; a range "A-B" is the printed from/to pair.
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`). Some rows cite more than one page where several filings print the same item.
- `amount_printed` is the text on the page. `amount_value` repeats it as a plain number for sorting. Nothing is summed; printed totals are in `printed_totals.csv`.
- No residence addresses or birth years.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack are not included.

Ministry of Records is a records-only research desk.
