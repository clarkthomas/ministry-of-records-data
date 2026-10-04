# Data files: FARA #7653, Show Faith by Works, LLC

CSV files of every row the registrant's DOJ FARA eFile filings print, used in the research pack for FARA #7653. Exported 2026-10-03 from filings pulled 2026-10-02 (index pulled again 2026-10-03; no new documents).

| File | Rows | What it holds |
|---|---|---|
| receipts.csv | 7 | The registration receipt and the six supplemental receipt rows. |
| disbursements-part1.csv | 187 | Disbursements rows 1-187: the registration's one summary row ("multiple" payees) and supplemental appendix rows, in printed order, repeated rows included. |
| disbursements-part2.csv | 187 | Disbursements rows 188-374 (supplemental appendix, printed order). |
| disbursements-part3.csv | 185 | Disbursements rows 375-559 (supplemental appendix, printed order). |
| disbursements-part4.csv | 184 | Disbursements rows 560-743 (supplemental appendix, printed order). |
| contacts.csv | 7 | Supplemental Item 12 entries. |
| principals.csv | 4 | The foreign principal and the three Havas entries as printed. |
| printed_totals.csv | 6 | Each total as the filings print it. |
| contributions.csv | 4 | Political contributions as reported to FARA. |

The disbursements table (743 rows) is split into four files so each stays under the upload size limit. Each part repeats the header row; the `row` column runs 1-743 across the parts, so the parts can be joined in order.

**Rules**

- One row per printed item, copied as printed (spelling included). Dates are as printed; a range "A-B" is the printed from/to pair.
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`). Some rows cite two pages where two filings print the same item.
- `amount_printed` is the text on the page. `amount_value` repeats it as a plain number for sorting. Nothing is summed; printed totals are in `printed_totals.csv`.
- Names of private individuals who are not filers are replaced with "[individual payee; name not reproduced]" (30 rows). No residence addresses, bank details or birth years.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack are not included.

**Changes**

- 2026-10-04: `note` added to receipts.csv rows 1, 2, 3 and 5. Rows 1 and 2: whether the 09/18/2025 registration receipt and the 09/27/2025 supplemental line ($325,881.00 each) are the same transfer is UNKNOWN. Rows 3 and 5 (10/10/2025 and 12/30/2025) are separate printed receipts. No figure changed.

Ministry of Records is a records-only research desk.
