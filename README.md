# MMM Marketing Hub dashboard

A static dashboard (GitHub Pages) for MMM marketing, CRM and performance.

- `index.html`: the whole page (HTML, CSS and vanilla JS, no build step). It loads `data.json` on open.
- `data.json`: all numbers and tables. This is the only file that changes day to day.

## Daily update
Mini Max regenerates `data.json` from fresh Whop, Buffer and post-results data with
`build_data.py` (kept on the bot's box), then commits just `data.json` to `main`.
GitHub Pages republishes within a minute or two. "Last updated" at the top shows the London time of the update.

## Privacy
This repo is public, so `data.json` holds counts and anonymised rows only (for example "Trialist, Perfect Entry"). No member names, handles or emails.

Education only. Not financial advice.
