# Aakrithi Cement — Billing (Offline Shop)

Single-file offline billing app for a cement shop.

## Files
- `index.html` — main app (open this in a browser)
- `cement.html` — same app (alternate filename)

## Usage
Open `index.html` directly in your browser, or host on GitHub Pages / Netlify.

All data (bills, stock, ledger, accounts, expenses) is saved in the browser's localStorage and persists across sessions. Use the in-app **⬇ Export** / **⬇ Download (CSV)** / **⬆ Send to Google Sheets** features for backup.

## Features
- Sell Cement (POS) with cart
- Quick Bill (tax invoice) with PDF export
- Saved Bills (print, PDF, attach bill PDF)
- Stock management with edit + date
- Remaining Stock view
- Ledger (customers/suppliers)
- Accounts (daily/monthly/yearly sales, expenses, purchases, income vs expense)
- Export/Import JSON backup
- Google Sheets sync (via Apps Script)
