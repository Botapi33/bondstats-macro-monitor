# Macro Monitor

A live GitHub Pages dashboard for tracking major sovereign yields and cross-country macro bond spreads using the BondStats global yield feed.

## What this tool does

This dashboard provides a live macro bond overview based on current 10-year sovereign yields across countries.

It shows:

- major developed market yields
- key global yield spreads
- eurozone benchmark spreads
- regional yield averages
- a macro watchlist of the most important sovereign markets

## Why this version is better

The older BondStats Macro Monitor page used fixed values and simplified static blocks.

This GitHub version reads directly from the live BondStats JSON feed and updates automatically.

## Live data source

The dashboard reads from:

`https://botapi33.github.io/bondstats-global-yields/global_yields.json`

## Files

- `index.html`
- `README.md`
- `.nojekyll`

