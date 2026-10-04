# Data files: FARA #7653, Show Faith by Works, LLC

CSV files of every row the registrant's DOJ FARA eFile filings print, used in the research pack for FARA #7653. Exported 2026-10-03 from filings pulled 2026-10-02 (index pulled again 2026-10-03; no new documents).

| File | Rows | What it holds |
|---|---|---|
| receipts.csv | 7 | The registration receipt and the six supplemental receipt rows. |
| disbursements.csv | 743 | The registration's one summary row ("multiple" payees) and the 742 supplemental appendix rows, in printed order, repeated rows included. |
| contacts.csv | 7 | Supplemental Item 12 entries. |
| principals.csv | 4 | The foreign principal and the three Havas entries as printed. |
| printed_totals.csv | 6 | Each total as the filings print it. |
| contributions.csv | 4 | Political contributions as reported to FARA. |

**Rules**

- One row per printed item, copied as printed (spelling included). Dates are as printed; a range "A-B" is the printed from/to pair.
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`). Some rows cite two pages where two filings print the same item.
- `amount_printed` is the text on the page. `amount_value` repeats it as a plain number for sorting. Nothing is summed; printed totals are in `printed_totals.csv`.
- Names of private individuals who are not filers are replaced with "[individual payee; name not reproduced]" (30 rows). No residence addresses, bank details or birth years.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack are not included.

Ministry of Records is a records-only research desk.
