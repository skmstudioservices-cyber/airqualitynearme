# airqualitynearme

AQI Near Me — live air quality (US AQI, PM2.5, PM10) of 15 Indian cities on a colour-coded map. Free, no login. Data: Open-Meteo (CAMS).

**Live:** https://airqualitynearme.pages.dev

Static single-page site on Cloudflare Pages (free tier). Live data is fetched client-side from free, keyless public APIs — no server, no Workers quota, no secrets.

## Files
- index.html — the whole site (Leaflet + OpenStreetMap, with attribution)
- robots.txt — AI-bot blocked, sitemap referenced
- sitemap.xml — homepage URL

Security: GSC verification tag pre-pasted (account-wide token); no secrets, no tracking, no PII collected.
