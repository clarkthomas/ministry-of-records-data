# Data files: FARA #7552, SKDKnickerbocker LLC (Israel Ministry of Foreign Affairs)

CSV files of every receipt, printed total, political contribution, principal and document used in the research pack for FARA #7552. Exported 2026-10-04 from filings in the DOJ bulk document index dated 10/04/2026. The registration names one foreign principal and ended on 08/29/2025.

| File | Rows | What it holds |
|---|---|---|
| receipts.csv | 3 | The three receipts "From Whom: Israeli Ministry of Foreign Affairs," $50,000.00 each (06/03, 06/11 and 07/08/2025), for the period ending 08/31/2025. |
| printed_totals.csv | 2 | The Item 14(a) subtotal ($150,000.00) and Total ($ 150,000.00), as printed. |
| contributions.csv | 5 | Political contributions reported to FARA (Registration Item 10(c); Supplemental Item 15(c)). |
| principals.csv | 2 | The Israel Ministry of Foreign Affairs, and HAVAS as named in the filed contract. |
| documents.csv | 17 | Every eFile document for #7552, with received date, page count and URL. |

**Rules**

- One row per printed item, copied as printed (spelling included). Dates are as printed. `amount_value` is the printed amount as a number, for sorting only; rows are never added.
- `page_cite` links to the eFile PDF page that prints the row (`#page=N`).
- The three receipts, the subtotal and the Total are the same money printed three ways; they must not be added.
- The filings print no disbursements. The contact log (Item 12) is not exported because some rows name individual people; the pack gives its counts.
- No residence addresses, telephone numbers, email addresses or birth years.
- These files hold FARA filing data only. The LDA, FEC and business-registry results described in the pack are not included.

Ministry of Records is a records-only research desk.
