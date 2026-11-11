# Aakrithi Homemart — Cement Billing (Offline Shop)

Single-file offline billing app for the cement shop.

## Files
- `index.html` — main app (open this in a browser / GitHub Pages serves this)
- `cement.html` — same app (alternate filename)
- `README.md` — this file

## Usage
Open `index.html` directly in your browser, or host on GitHub Pages / Netlify / Vercel.

All data (bills, stock, ledger, accounts, expenses, calc history) is saved in the
browser's `localStorage` and persists across sessions. Use the in-app backup/export
features for safety.

## Features
- 🏪 **Sell Cement (POS)** with cart → Make Bill
- 🧾 **Quick Bill** (tax invoice) with item dropdown from stock, PDF download, Print
- 📁 **Saved Bills** (print, PDF, view, attach bill PDF)
- 📦 **Stock** management (add/edit/delete, date, retail/wholesale rates, GST, attach bill)
- 📊 **Remaining Stock** live view
- 📒 **Ledger** (customers/suppliers with running balances)
- 💰 **Accounts** (daily/monthly/yearly sales, expenses, purchases, income vs expense)
- 📑 **Reports** (Profit & Loss, GST summary, Day Book, Balance Sheet)
- 🧮 **Calculator** (basic + keyboard support, expression line, history with copy)
- 🏷️ **Price Check** (look up stock price, load into calculator)
- 🗂 **Data Backup** (Export/Import JSON)
- 📊 **Google Sheets Sync** (via Apps Script)
- ⬇ **Download** Stock / Remaining / Ledger / Sales / Expenses as CSV

## Company
- Name: AAKRITHI HOMEMART PRIVATE LIMITED
- Cement Shop: KALLEPADAM, PALAKKAD, KERALA - 680587
- Registered Office: Door No 14/1713, Krishnakripa Building, Opp KAM Jewellery, Vadakkancherry, Palakkad, Kerala - 678683
- GSTIN: 32ABFCA1312C1ZN

## Notes
- Works offline (single HTML file, no backend required).
- PDF export uses html2canvas + jsPDF from CDN (needs internet for that feature).
- Data is per-browser (localStorage). Use Export JSON / Google Sheets sync to share or back up.
