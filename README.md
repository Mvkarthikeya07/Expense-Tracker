# 💰 Expense Tracker

A desktop expense tracker that does three things flawlessly: **log it, filter it, visualize it.** Built with Tkinter and backed by a persistent CSV ledger.

## Features
- Add expenses with date, description, and amount (₹)
- Filter spending history by custom date ranges
- One-click **monthly spending bar chart** via Matplotlib
- Input validation on every field — no malformed entries reach storage
- Persistent CSV storage — your data survives every restart

## Tech Stack
`Python` · `Tkinter` · `Matplotlib` · `CSV`

## Run It
```bash
pip install matplotlib
python expense_tracker_gui.py
```

## Why It's Solid
- Zero database setup — CSV is the database
- Strict date/amount validation prevents silent data corruption
- Visual summaries turn raw rows into actual insight

## Roadmap
- [ ] Category-based expense tagging
- [ ] Export filtered views to PDF
- [ ] Multi-currency support

---
*Track it, filter it, see it. Three clicks, full clarity.*
