# Waterfall

A budget and debt pay-down planner. Enter your income for the month and it recommends which bills, minimum payments, and debts get paid first — supports variable weekly/4-weekly/monthly bills, multiple income sources, 0% intro-rate credit cards, avalanche/snowball payoff strategies, and tracking actual vs. planned payments.

**Live site:** see the GitHub Pages link in the repo's "About" section (Settings → Pages once enabled).

## Data storage

This app was originally built as a Claude Artifact, where it saves data through Claude's built-in cloud database. Hosted here as a standalone static site, it falls back to your browser's `localStorage` instead — your data stays in whichever browser you use it in, isn't synced across devices, and will be lost if you clear that browser's site data for this page.

## Running locally

It's a single self-contained `index.html` file — just open it in a browser, or serve the folder with any static file server.
