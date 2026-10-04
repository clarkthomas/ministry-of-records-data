# Ministry of Records: data files

Ministry of Records is a records-only research desk (solo operator). This repository holds the CSV data files that accompany its free sample research packs on registrants under the Foreign Agents Registration Act (FARA).

## What is here

- One folder per FARA registration number (`fara-<number>/`).
- Each CSV row is one item as printed in a U.S. government filing, copied as printed, including its spelling.
- Each row carries a `page_cite` link to the page of the filing that prints it (DOJ FARA eFile, `https://efile.fara.gov/docs/...pdf#page=N`). `documents.csv` lists the filings themselves.
- Each folder's `README.md` describes its files, row counts and rules.

## Rules

- Amounts are as printed. `amount_value` is a number parsed from the printed amount, for sorting only. Rows are never added together, and no totals are computed; a total appears only where a filing prints one (`printed_totals.csv`).
- No street addresses, telephone numbers, email addresses or birth years. No contributor city or state.
- Sources are original U.S. government filings only (DOJ FARA eFile). Data from other public databases (lobbying disclosures, FEC, business registries) is described in the packs and is not included here.
- A row reports what a filing says; it is not a finding that the statement is true or complete.

## Folders

| Folder | Registrant |
|---|---|
| [fara-7631](fara-7631/) | Genesis 21 Consulting LLC |
| [fara-7639](fara-7639/) | Jonathan Charles Goldstein |
| [fara-7745](fara-7745/) | Sniper Advertising Services |
| [fara-7653](fara-7653/) | Show Faith by Works |
| [fara-7652](fara-7652/) | Bridges Partners |
| [fara-7768](fara-7768/) | Pearson Unlimited, LLC |
| [fara-7518](fara-7518/) | GlobalPoint International (Stark Aerospace engagement) |
| [fara-7597](fara-7597/) | K&L Gates, LLP |
| [fara-7485](fara-7485/) | Robert Goetsch (Thoth Technologies LLC) |
| [fara-7641](fara-7641/) | Bluelight Strategies |
| [fara-7553](fara-7553/) | Targeted Communications Global LLC |
| [fara-7662](fara-7662/) | Davis Media NY LLC |
| [fara-7664](fara-7664/) | American Future Fund |

## Corrections

If a row does not match its cited page, open an issue with the folder, file, row number and the page link. Corrections are logged in the folder's README with the date.

## License

The compilation, the column structure and the README text are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Attribution: "Ministry of Records". The underlying filings are U.S. government records.
