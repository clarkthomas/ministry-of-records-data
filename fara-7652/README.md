# Data files: FARA #7652, Bridges Partners LLC

CSV files of every row the registrant's DOJ FARA eFile filings print, used in the research pack for FARA #7652. Exported 2026-10-03 from filings pulled 2026-10-02 (index pulled again 2026-10-03; no new documents).

| File | Rows | What it holds |
|---|---|---|
| receipts.csv | 1 | The one receipt, 07/03/2025. |
| disbursements.csv | 41 | The 16 registration appendix rows, the row added by the amendment, and the 24 supplemental appendix rows. |
| principals.csv | 3 | The foreign principal, the Havas entity on the order, and the client named on the order. |
| printed_totals.csv | 8 | Each total as the filings print it. |
| contacts.csv | 0 | Header only: the 2026 Exhibit B prints "No Political Activity Contacts to Report," and the supplemental's table is blank. |
| contributions.csv | 0 | Header only: every contribution item reads No. |

**Rules**

- One row per printed item, copied as printed (spelling included). Dates are as printed; a range "A-B" is the printed from/to pair.
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`). Some rows cite two pages where two filings print the same item.
- `amount_printed` is the text on the page. `amount_value` repeats it as a plain number for sorting. Nothing is summed; printed totals are in `printed_totals.csv`.
- Names of private individuals who are not owners or filers are replaced with "Individual 1" to "Individual 5" (13 rows). No residence addresses, bank details or birth years.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack are not included.

Ministry of Records is a records-only research desk.
