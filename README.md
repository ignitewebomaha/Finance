# PocketPair — Shared Monthly Expense Tracker (vanilla JS)

A simple, mobile-friendly expense tracker you can open in VS Code with Live Server. Add daily purchases, see a pie chart of category percentages for the selected month, export CSV, and backup/restore JSON. Data is saved in your browser's localStorage.

## Quick start
1. Extract this folder.
2. Open it in VS Code.
3. Install the **Live Server** extension (if you don't have it).
4. Right-click `index.html` → **Open with Live Server**.

## Features
- Add purchases (date, amount, category, note)
- Month filter
- Pie chart of spending by category (Chart.js via CDN)
- Edit / delete entries
- Custom categories (add/remove)
- Export CSV (for Google Sheets/Excel)
- Backup/restore JSON
- Mobile-first, dark UI

## Sharing with your wife
This version stores data separately per browser. Options to share:
- **Simplest:** Each of you keeps your own data and you occasionally export CSV and combine in Google Sheets.
- **Shared browser profile:** Use the same browser profile on a shared laptop.
- **Next step:** Swap localStorage for a shared backend (Supabase / Firebase / Google Sheets). The UI can stay the same — just replace the storage calls.

## File overview
- `index.html` — markup and layout
- `styles.css` — dark, mobile‑first styles
- `script.js` — app logic + Chart.js pie chart

---

If you want, I can upgrade this to sync live between devices using Supabase (free tier) in a follow-up.
