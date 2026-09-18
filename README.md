# HEATWARD Frontend — Neon Green / Black Build

A React + Vite HEATWARD dashboard using the supplied 141-ward Kolkata GeoJSON locally.

## Run

```bash
npm install
npm run dev
```

## Visual system

- Black is the primary interface foundation.
- Neon green `#39FF14` is the HEATWARD brand/system accent.
- Conventional semantic warning colors are preserved: yellow for moderate, orange for high, red for extreme/critical.
- Risk colors are never replaced by brand green.
- No Google Maps or external raster basemap is used. The map is rendered from the supplied ward GeoJSON.

## Current model coverage

The prototype uses the supplied peak-day outputs for W01–W10. The remaining wards are rendered as neutral geometry rather than being assigned invented model values.

## Typography

Inter = UI, Roboto = data, Montserrat = headings, Impact = risk emphasis, 72 = brand slot with fallback until the actual font file is supplied.
