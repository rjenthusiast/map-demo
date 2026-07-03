# WanderCebu — Map Discovery Demo

An interactive tourism-marketplace map demo: custom markers, search & filters, and location-based discovery, themed around Cebu, Philippines.

**Built with:** [MapLibre GL JS](https://maplibre.org/) — the open-source engine with an API identical to Mapbox GL JS. No API key required.

## Features

- 🗺️ **Custom markers** — branded pins colour-coded by category (hotels, tours, events, transport)
- 🔎 **Search & filters** — live text search, multi-select category chips, max-price slider, min-rating stars, and sorting
- 📍 **Location-based discovery** — "Near me" ranks the nearest listings by real distance
- 🔗 **Two-way sync** — click a marker to highlight its card; click a card to fly the map and open a booking popup

## Run locally

It's a single self-contained file — just open `index.html` in any browser, or serve it:

```bash
python -m http.server 5177
# then open http://localhost:5177
```

## Deploy on GitHub Pages

1. Create a new repository and push these files (see below).
2. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)**, then **Save**.
4. Your live demo will be at `https://<your-username>.github.io/<repo-name>/` within a minute.
