# GIFT City Retail Fund Screener

A static page that compares the retail funds available in GIFT City: Direct plan NAV, expense ratio, minimum investment, exit load, returns, benchmark, holdings, geography and sectors, with NAV growth charts and a compare view.

## Files

- `index.html` is the whole page.
- `lib/d3.min.js` is D3 v7, kept here so the page works without a CDN.
- `data/nav_latest.csv` holds the latest NAV for each fund.
- `data/navhist.csv` holds NAV history for the charts.
- `data/benchhist.csv` holds daily benchmark index levels for the active funds.
- `data/profile.csv` holds manager, costs, returns and benchmark returns.
- `data/alloc.csv` holds top holdings, countries and sectors.

## Notes

NAVs are the Direct plan subscription NAV in US dollars from each fund house's website. Benchmark returns marked as calculated are not published figures.

To view the page locally, run `python3 -m http.server` in this folder and open http://localhost:8000.
