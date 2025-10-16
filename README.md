# Frame3S Web Map (Leaflet + GitHub Pages)

This repository hosts the **Frame3S** public web map. It uses **Leaflet** and **GeoJSON** and can be published via **GitHub Pages** (static hosting, no logins required).

## How to publish
1. Put your GeoJSON files into `data/` and name them exactly:
   - `lwd_subregions_euregio.geojson`
   - `GMBA_Inventory_L8.geojson`
2. Commit & push.
3. Enable GitHub Pages: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, select `main` and `/ (root)`.
4. Open the URL shown by Pages — your map is live.

## Notes
- Basemap: **OpenStreetMap** (default). Optional **Esri World Imagery** included in layer control.
- Layer toggles appear top-right.
- Legend bottom-left, matching requested colors/line widths.
- Click features to see attributes.
- If files are large, consider simplifying geometries.
- GeoJSON should be WGS84 (EPSG:4326).

© 2025 Franz Wagner – University of Innsbruck – franz.wagner@uibk.ac.at
