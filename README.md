# Global Weather Center — SPC Outlooks V5

Static website for GitHub Pages. Uses official NOAA SPC outlook polygons.

## Update V5

- City labels placed before two-letter state codes so state text cannot crowd out cities.
- National/zoomed-out map prioritises major cities, while smaller cities appear on zoom in.
- Large, high-contrast city names with dark outlined text and two-letter state abbreviations.
- Keeps existing SPC outlook controls, basemap, zoom and default USA behaviour.

## Publish
Upload `index.html`, `style.css`, `app.js` and `README.md` to the root of the **same repository currently hosting the website**. Enable GitHub Pages from the `main` branch root. Look for **GWC LABELS V5** at the bottom to confirm the deployed version.

Requires internet access to load NOAA service, state outlines, and Leaflet.
