# Zulu (UTC) & US Time Zones — Live + Converter

A single-page, static web app that shows live clocks for UTC and US time zones, and converts any entered **Zulu (UTC)** datetime into each zone. No back end; no tracking.

## Features
- Live, real-time clocks (UTC, ET, CT, MT, AZ (no DST), PT)
- Converter: enter a UTC datetime → see each zone’s local time + offset
- Daylight Saving Time handled by the browser’s IANA time zone data
- Mobile-friendly, lightweight

## Customize
- **Time zones:** Edit the `ZONES` array near the bottom of `index.html`.
- **24‑hour time:** In the `fmt*` formatters, set `hour12:false`.
- **Styling:** Adjust CSS variables at the top (navy/blue palette).

## Privacy & telemetry
This page runs entirely in the browser. No analytics, no cookies, no data collection.

## License
MIT — see `LICENSE`.
