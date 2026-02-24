# BlueTree Marketing — Campaign Performance Report

Live site: [brian-report.netlify.app](https://brian-report.netlify.app)

## Overview

Static HTML report tracking Brian Rechtman's outbound campaign performance from August 2025 through February 2026. Built for BlueTree Marketing.

## What's in the report

- **KPI cards** — Total responses, Feb pace, meeting requests
- **Trend chart** — Monthly responses and responses/day (Chart.js)
- **Monthly breakdown table** — Aug 2025 – Feb 2026 with projections
- **February projection bars** — Visual comparison vs January

## Stack

- Plain HTML + CSS (no build step)
- [Chart.js 4.4.1](https://www.chartjs.org/) via CDN
- Google Fonts: DM Sans + Playfair Display
- Hosted on [Netlify](https://www.netlify.com/)

## Local development

Just open `index.html` in a browser — no dependencies to install.

## Deploy

```bash
netlify deploy --dir . --prod --site ab43a73e-bbe3-4502-b8d3-32a964bb4082
```

---

Built by [BlueTree Marketing](https://www.bluetreemarketing.com/)
