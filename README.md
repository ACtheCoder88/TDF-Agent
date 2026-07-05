# TDF Syndicate Agent — Dashboard (auto-published)

Live view: https://actiecoder88.github.io/TDF-Agent/

This repo contains only the **built dashboard** (static HTML + a data snapshot) —
no scripts, no database, no credentials. It's pushed automatically by the TDF
Syndicate Agent's refresh loop, so content updates without any manual step here.

Source project (private, not this repo) generates `index.html`, `data.json`, and
`data.js` from `tdf-agent/scripts/export_dashboard.py`.
