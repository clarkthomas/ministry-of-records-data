# Data files: FARA #7768, Pearson Unlimited, LLC

CSV files of every dollar figure, contribution, principal and document the registrant's DOJ FARA eFile filings print, used in the research pack for FARA #7768. Exported 2026-10-04 from filings in the DOJ bulk index dated 10/04/2026.

| File | Rows | What it holds |
|---|---|---|
| contributions.csv | 2 | One contribution (08/12/2026, $ 1,000.00), printed on the registration and on the short form. |
| planned.csv | 2 | The proposal's "$20,000 / month" retainer and the short form's "$ 20,000.00 per Month" salary. These are rates, not payments. |
| principals.csv | 2 | The foreign principal and its parent company, as printed. |
| documents.csv | 3 | The three eFile documents, with received date, page count and URL. |

**Rules**

- One row per printed item, copied as printed (spelling included). Dates are as printed.
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`).
- `amount_printed` is the text on the page. `amount_value` repeats it as a plain number for sorting. Nothing is summed.
- The registrant has filed no receipts, disbursements, activity contacts or printed totals, so those files are not included.
- No residence addresses, street addresses or birth years.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack are not included.

Ministry of Records is a records-only research desk.
