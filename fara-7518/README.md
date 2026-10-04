# Data files: FARA #7518, GlobalPoint International (Stark Aerospace engagement)

CSV files of every receipt, printed total, contract term, principal and document used in the research pack for FARA #7518. Exported 2026-10-04 from the DOJ bulk document index dated 10/04/2026. The pack covers the Stark Aerospace Inc. engagement only.

| File | Rows | What it holds |
|---|---|---|
| receipts.csv | 1 | The Stark Aerospace receipt: $90,305.00 on 12/12/2025, "Consulting Fees (November 2025 and FARA Filing Fees)". |
| printed_totals.csv | 3 | The Item 14(a) total for all principals ($ 459,735.00) and the two appendix subtotals ($90,305.00 for Stark; $369,430.00 for the Cote d'Ivoire principal) as printed for the period ending 01/31/2026. |
| planned.csv | 5 | Contract terms: US$ 270,000; US$ 45,000 per month; up to US$ 100,000 (2025 contract); $180,000 and up to $100,000 (2026 renewal). These are terms, not payments. |
| principals.csv | 1 | Stark Aerospace Inc., as printed. |
| documents.csv | 24 | Every eFile document for #7518 in the index, with received date, page count and URL (the pack reads 8 of them). |

**Rules**

- One row per printed item, copied as printed (spelling included). Dates are as printed. `amount_value` is the printed amount as a number, for sorting only; rows are never added.
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`).
- The $90,305.00 receipt and the $90,305.00 Stark subtotal are the same money printed twice; they must not be added.
- The filings print no disbursements, contacts or political contributions for Stark, so those files are not included.
- No addresses, telephone numbers, email addresses or birth years.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack are not included.

Ministry of Records is a records-only research desk.
