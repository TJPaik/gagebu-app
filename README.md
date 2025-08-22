# gagebu-app

Paste spreadsheet data (Excel/Google Sheets) to summarize a household ledger in the browser. Data is stored locally.

Demo: https://TJPaik.github.io/gagebu-app/

## Description
The app accepts pasted rows with date, memo, and amount, then shows summaries such as totals and per-period breakdowns. No backend is used; everything runs client-side.

## Usage
- Copy rows from your spreadsheet that include date, memo, and amount.
- Paste into the input area on the page.
- Add or remove items as needed and review the calculated summaries.
- Data is saved to `localStorage` and persists in the same browser.

## Data format (expected)
- `date`: ISO-like string (e.g., 2025-08-01) or a recognizable date format
- `memo`: free text
- `amount`: number (commas are ignored)

## Privacy
- No network upload of your pasted data.
- All data remains in the browser unless you export or copy it out.

## License
MIT — see `LICENSE`.
