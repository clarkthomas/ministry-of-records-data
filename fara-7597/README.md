# Data files: FARA #7597, K&L Gates, LLP

CSV files of every receipt, printed total, contract term, contribution, principal and document that the registrant's DOJ FARA eFile filings print, used in the research pack for FARA #7597. Exported 2026-10-04 from the eFile document index for #7597 pulled that day.

| File | Rows | What it holds |
|---|---|---|
| receipts.csv | 4 | The four Item 14(a) receipt rows ($25,000.00 each) from the two supplemental statements. |
| printed_totals.csv | 2 | The two receipt totals the supplementals print ($50,000.00 for each period). |
| planned.csv | 8 | Contract and letter terms: the Japan letters ($25,000; $75,000; $4,520.54; $150,000 if extended), the Morgulchik letter ($10,000 fixed FARA fee; $15,000/month anticipated retainer; $1535.00 hourly rate) and the short form's "$ 15,000.00 per Month" fee. These are terms, not payments. |
| contributions.csv | 2 | The one political contribution, printed twice (registration Item 10(c) and Bolin's short form Item 15). |
| principals.csv | 2 | The two foreign principals, as printed. |
| documents.csv | 15 | The fifteen eFile documents, with received date, page count and URL. |

**Rules**

- One row per printed item, copied as printed (spelling included). Dates are as printed. `amount_value` is the printed amount as a number, for sorting only; rows are never added.
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`).
- The contribution is printed on two documents; the two rows are the same contribution and must not be added.
- The registrant reports no disbursements and no activity contacts, so those files are not included.
- No addresses, telephone numbers, email addresses, birth years or citizenship details.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack are not included.

Ministry of Records is a records-only research desk.
