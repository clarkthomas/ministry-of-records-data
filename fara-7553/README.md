# Data files: FARA #7553, Targeted Communications Global LLC

CSV files of every dollar figure, contact, contribution, principal and document the registrant's DOJ FARA eFile filings print, used in the research pack for FARA #7553. Exported 2026-10-04 from filings in the DOJ bulk index dated 10/04/2026.

| File | Rows | What it holds |
|---|---|---|
| receipts.csv | 7 | The seven receipt rows, supplemental received 06/30/2026 (period ending 03/31/2026). |
| disbursements.csv | 42 | 41 appendix rows (supplemental 06/30/2026) and one $90.00 row (supplemental 12/11/2025). Four individual payees are shown as Individual 1 to 4. |
| contacts.csv | 201 | Media contacts: 24 before registration (Exhibit B, MFA; outlet only), 60 (period ending 09/30/2025) and 117 (period ending 03/31/2026). |
| contributions.csv | 12 | Political contributions as printed. The two Gorman rows of January 2025 are printed on both the registration and his short form, so they appear twice. |
| printed_totals.csv | 3 | The totals the supplementals print, each with its own page. |
| planned.csv | 7 | The seven lines of the Havas Media Germany GmbH work order dated 27/04/2026. These are contract lines, not payments. No total is printed. |
| principals.csv | 5 | The two foreign principals and three intermediaries, as printed. |
| documents.csv | 23 | The 23 eFile documents, with received date, page count and URL. |

**Rules**

- One row per printed item, copied as printed (spelling included). Dates are as printed.
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`).
- `amount_printed` is the text on the page. `amount_value` repeats it as a plain number for sorting. Nothing is summed; do not add receipts, disbursements and work-order lines together.
- No residence addresses, street addresses, birth years, journalist names or individual payee names.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack are not included.

Ministry of Records is a records-only research desk.
