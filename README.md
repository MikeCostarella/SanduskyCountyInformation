# Sandusky County Information

A searchable, filterable directory of meaningful links across **Sandusky County, Ohio** (county seat: Fremont) — government, education, health, business, community, recreation, and news.

## What's inside

```
SanduskyCountyInformation/
├── react-app/                    # the Vite + React browsing app
│   └── src/data/links.js         # single source of truth for all links
├── data/
│   └── sandusky_county_links.csv # the same directory as a spreadsheet
└── README.md
```

## Run it

```bash
cd react-app
npm install
npm run dev
```

Then open the URL Vite prints (usually http://localhost:5173/SanduskyCountyInformation/).

## Add or edit links

Edit `react-app/src/data/links.js`. Keep `data/sandusky_county_links.csv` in sync if you rely on the spreadsheet.

## Notes

- Links were researched and reviewed on July 18, 2026 (16 links).
- This is a community reference tool, not an official government site.
