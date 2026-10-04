# Data files: FARA #7485, Robert Goetsch (Thoth Technologies LLC)

CSV files of every compensation term, principal and document that the registrant's DOJ FARA eFile filings print, used in the research pack for FARA #7485. Exported 2026-10-04 from the DOJ bulk document index dated 10/04/2026.

| File | Rows | What it holds |
|---|---|---|
| planned.csv | 2 | The two printed compensation terms: the finder agreement's "eight percent (8%) of the Revenues" (Exhibit A/B p. 11) and the short form's "Commission at 8.00 % of gross sales" (p. 2). These are rates, not payments. |
| principals.csv | 1 | The foreign principal, Combatica LTD (Israel), as printed. |
| documents.csv | 5 | The five eFile documents, with received date, page count and URL. |

**Rules**

- One row per printed item, copied as printed (spelling included). Dates are as printed. `amount_value` is the printed rate as a number, for sorting only; rows are never added.
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`).
- The filings report no receipts, disbursements, political contributions or activity contacts, so those files are not included.
- No addresses, telephone numbers, email addresses or birth years.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack (all zero) are not included.

Ministry of Records is a records-only research desk.
