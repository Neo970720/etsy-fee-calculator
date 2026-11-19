# Etsy Fee & Profit Calculator (2026)

A free, single-file calculator for Etsy sellers. Enter your price, shipping, item cost and
Offsite Ads setting, and it shows every fee on one screen: listing, transaction, payment
processing, regulatory operating fee, Offsite Ads and the VAT that is charged on fees —
for all 32 Etsy seller countries, using the rates published on Etsy's own help pages on
**20 November 2026**.

- **Live page:** https://neo970720.github.io/etsy-fee-calculator/
- **No build step, no dependencies, no tracking.** `index.html` is the whole app.
- Includes a "recommended price" mode that works backwards from a target margin.

Built by Sheetwright. The paid companion, **Etsy True Profit OS** ($39, 10-sheet Excel/Google
Sheets workbook), is at https://sheetwrightstudio.gumroad.com/l/etsy-true-profit-os-2026

Not affiliated with, endorsed by, or sponsored by Etsy, Inc. "Etsy" is a trademark of Etsy, Inc.
The calculator is an estimate, not accounting or tax advice.

## Local preview

Open `index.html` in a browser, or:

```
python3 -m http.server 8000
```

## Files

| File | Purpose |
|---|---|
| `index.html` | The calculator (HTML + CSS + JS in one file) |
| `_headers` | Optional header rules (used by Cloudflare Pages; ignored by GitHub Pages) |
| `robots.txt` | Allows all crawlers |
| `.nojekyll` | Serve files as static assets, no Jekyll processing |
