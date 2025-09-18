# Zulu (UTC) & US Time Zones — Live + Converter

A single-page, static web app that shows live clocks for UTC and US time zones, and converts any entered **Zulu (UTC)** datetime into each zone. No back end; no tracking.

## Features
- Live, real-time clocks (UTC, ET, CT, MT, AZ (no DST), PT)
- Converter: enter a UTC datetime → see each zone’s local time + offset
- Daylight Saving Time handled by the browser’s IANA time zone data
- Mobile-friendly, lightweight

## Quick start
Open `index.html` in any modern browser.

## Deploy to GitHub Pages (free)
1. Create a new GitHub repo (e.g., `zulu-converter`).
2. Upload these files: `index.html`, `404.html`, `README.md`, `.gitignore`, `LICENSE`.
3. Repo → **Settings → Pages** → **Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: `main` (or `master`), Folder: `/root`
4. Wait ~1 minute. Your site will be at:
   `https://<your-username>.github.io/<repo-name>/`

## Add to Microsoft Teams as a tab
1. Copy the site URL from GitHub Pages (HTTPS).
2. In your Teams channel → **+** (Add a tab) → **Website**.
3. Paste the URL, give it a name (e.g., “Zulu & US Time”), and save.

> Note: Some organizations block external URLs in Teams tabs. If so, host this on an approved internal platform (e.g., Azure Static Website) instead.

## Customize
- **Time zones:** Edit the `ZONES` array near the bottom of `index.html`.
- **24‑hour time:** In the `fmt*` formatters, set `hour12:false`.
- **Styling:** Adjust CSS variables at the top (navy/blue palette).

## Privacy & telemetry
This page runs entirely in the browser. No analytics, no cookies, no data collection.

## License
MIT — see `LICENSE`.
