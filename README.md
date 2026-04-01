<p align="center">
  <img src="https://img.shields.io/badge/status-live-brightgreen" alt="Live">
  <img src="https://img.shields.io/badge/hosting-Cloudflare%20Pages-F38020" alt="Cloudflare Pages">
  <img src="https://img.shields.io/badge/build-zero--config-blue" alt="Zero Config">
  <img src="https://img.shields.io/badge/framework-vanilla-yellow" alt="Vanilla HTML">
</p>

<h1 align="center">916 Notary</h1>
<p align="center"><strong>Sacramento's On-Demand Mobile Notary Network</strong></p>
<p align="center">
  <a href="https://916notary.com">916notary.com</a>
</p>

<p align="center">
  <img src="preview.png" alt="916 Notary Preview" width="700">
</p>

---

## About

916 Notary is a single-page marketing site for a mobile notary service covering the entire Sacramento 916 area code. The site is designed to look like a real-time dispatch operations dashboard — with a live interactive map, simulated agent tracking, zone coverage ETAs, and an activity feed — all running client-side with no backend.

The domain and site are currently listed **for sale** as a turnkey package.

## Features

- **Interactive Leaflet Map** — Full-screen dark-themed map of Sacramento County with animated agent markers, coverage radius circles, and zone boundaries. Uses OpenStreetMap tiles with a CartoDB dark basemap.

- **Simulated Real-Time Dispatch** — Fake-but-convincing "live" agent dots that pulse and move across the map. Activity feed shows agents completing signings across different Sacramento neighborhoods. All generated client-side with randomized timing.

- **Zone Coverage Grid** — 16-zone ETA display showing estimated response times (12m–34m) across Sacramento neighborhoods from Downtown to Granite Bay.

- **Service Catalog** — Detailed pricing for loan signings ($150+), POA ($15/sig), apostille ($60+), healthcare directives, legal documents, and corporate services.

- **"How It Works" Flow** — 4-step visual guide: Request Online > Agent Dispatched > Track on Map > Signed & Sealed.

- **SEO & Schema Markup** — Full `ProfessionalService` JSON-LD schema, optimized meta tags, canonical URL, and area-served structured data for local search.

- **Responsive Design** — Mobile-first layout that collapses the sidebar below the map on smaller screens. Status ticker bar at the bottom shows live stats.

- **Domain For Sale Banner** — Persistent red strip at the top with a "Make Offer" CTA and mailto link.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Vanilla HTML/CSS/JS — single file, no build step |
| Map | [Leaflet.js](https://leafletjs.com) 1.9.4 with CartoDB dark tiles |
| Fonts | JetBrains Mono (data/UI), Inter (body) via Google Fonts |
| Favicon | Inline SVG data URI (gold "916" badge) |
| Hosting | Cloudflare Pages |
| DNS | Cloudflare |

## Project Structure

```
916notary.com/
  index.html      # The entire site — HTML, CSS, JS all inline
  preview.png     # Screenshot for this README
  CLAUDE.md       # AI assistant context
  README.md       # You are here
```

## Deploy

```bash
wrangler pages deploy . --project-name=916notary-com
```

## License

Private project. All rights reserved.
