# Data files: FARA #7394, IPG DXTRA, Inc. d/b/a Weber Shandwick (Israel Ministry of Finance engagement)

CSV files of every receipt, printed total, principal and document used in the research pack for FARA #7394. Exported 2026-10-04 from filings in the DOJ bulk document index dated 10/04/2026. The pack covers the Ministry of Finance of the State of Israel engagement only.

| File | Rows | What it holds |
|---|---|---|
| receipts.csv | 4 | The four Ministry of Finance receipts printed for the period ending 04/30/2026 (02/23/2026 to 04/21/2026), each "Consulting fee". |
| printed_totals.csv | 2 | The Item 14(a) total for all principals ($ 612,827.51) and the Ministry of Finance appendix subtotal ($555,675.03), as printed. |
| principals.csv | 1 | The Ministry of Finance of the State of Israel, as printed. |
| documents.csv | 4 | The four eFile documents the pack reads, with received date, page count and URL. |

**Rules**

- One row per printed item, copied as printed (spelling included). Dates are as printed. `amount_value` is the printed amount as a number, for sorting only; rows are never added.
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`).
- The all-principals total includes another principal's receipts; it is not a Ministry of Finance figure. The Ministry of Finance subtotal and the four receipt rows are the same money printed twice; they must not be added.
- The filings print no disbursements, contacts or political contributions for this principal, so those files are not included.
- No residence addresses, telephone numbers, email addresses or birth years.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack are not included.

Ministry of Records is a records-only research desk.
