# FleetOps — Fleet Monitoring Dashboard (Portfolio Demo)

**[Open the live demo](https://YOUR-USERNAME.github.io/evdtr-fleet-demo/)** · Replace `YOUR-USERNAME` after publishing.

A standalone, interactive fleet operations dashboard adapted for a public software portfolio. Built with vanilla HTML, CSS, JavaScript, and Chart.js.

> **Synthetic data only.** This repository does not contain production datasets, credentials, private spreadsheets, or proprietary Google Apps Script backend logic. The demo is not affiliated with or endorsed by any employer.

## Features

- Overview: fleet availability, utilization, idle, travel and breakdown KPIs
- Equipment and date filters, charts and notifications
- Activity logs for Travel, Utilize, Idle and Breakdown
- Outlier review, average route travel, and wait monitoring
- CSV export
- Demo-only log editing and outlier corrections (not persisted to a server)
- Responsive sidebar and dashboard layout

## Run locally

Open `index.html` in a modern browser, or serve it locally:

```bash
python -m http.server 8000
```

Visit http://localhost:8000/.

## Publish to GitHub Pages

1. Create a **public** GitHub repository named `evdtr-fleet-demo`.
2. Upload `index.html`, `README.md`, `.nojekyll`, and `docs/` from this folder.
3. Open repository **Settings → Pages**.
4. Choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and Save.
5. Your website will be at `https://YOUR-USERNAME.github.io/evdtr-fleet-demo/` after deployment.
6. Update the live-demo link at the top of this README.

## Repository layout

```
evdtr-fleet-demo/
├── index.html          # Standalone dashboard, UI and synthetic data
├── README.md           # Project overview and deployment steps
├── .nojekyll           # GitHub Pages static-site marker
└── docs/
    └── PORTFOLIO.md   # Suggested portfolio case study
```

## Notes and limitations

- Data is generated for demonstration, not a live fleet feed.
- Some KPIs are illustrative summary metrics and may not recalculate for every filter combination.
- Edits exist only in the current browser session and can reset when reloading.
- The dashboard loads Chart.js and Google Fonts from public CDNs, so internet access is needed for those assets.
- The original Google Apps Script backend is **not included** in this public repository.

## Tech stack

HTML5 · CSS3 · JavaScript (ES2022) · Chart.js · GitHub Pages

## License

Only publish code and assets you own or have permission to share. Verify your employment and intellectual-property obligations before making this repository public.
