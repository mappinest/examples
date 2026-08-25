# Mappinest Examples

Public examples for using Mappinest with common map clients.

Use this repo with the [Mappinest map client guides](https://www.mappinest.com/docs/guides). The standalone HTML examples match the JavaScript examples shown in the docs.

These examples show the two main integration paths:

- Maps API through StyleJSON URLs.
- Tiles API through TileJSON and direct XYZ tile URLs.

## Examples

| Map client | Example | Path |
| --- | --- | --- |
| MapLibre GL JS | Load map style | `examples/maplibre-gl-js/stylejson-map-style` |
| MapLibre GL JS | Uploaded vector tileset | `examples/maplibre-gl-js/uploaded-vector-tileset` |
| MapLibre GL JS | Uploaded raster tiles | `examples/maplibre-gl-js/uploaded-raster-tiles` |
| Mapbox GL JS | Load map style | `examples/mapbox-gl-js/stylejson-map-style` |
| Mapbox GL JS | Uploaded vector tileset | `examples/mapbox-gl-js/uploaded-vector-tileset` |
| Mapbox GL JS | Uploaded raster tiles | `examples/mapbox-gl-js/uploaded-raster-tiles` |
| OpenLayers | Load map style | `examples/openlayers/stylejson-map-style` |
| OpenLayers | Uploaded vector tileset | `examples/openlayers/uploaded-vector-tileset` |
| OpenLayers | Uploaded raster tiles | `examples/openlayers/uploaded-raster-tiles` |
| Leaflet | Load map style | `examples/leaflet/stylejson-map-style` |
| Leaflet | Uploaded vector tileset | `examples/leaflet/uploaded-vector-tileset` |
| Leaflet | Leaflet.VectorGrid vector tileset | `examples/leaflet/leaflet-vectorgrid` |
| Leaflet | Uploaded raster tiles | `examples/leaflet/uploaded-raster-tiles` |

## Run locally

Install dependencies:

```bash
npm install
```

Start the local preview server:

```bash
npm run dev
```

Open one of the example folders from the Vite local server. Get a free Mappinest API key from API Keys & Access,
then replace `YOUR_MAPPINEST_KEY`. Mapbox GL JS examples also need `YOUR_MAPBOX_ACCESS_TOKEN`.
The uploaded vector examples use `mappinest.COUNTIES`, and the uploaded raster examples use
`mappinest.countries-raster` as sample tilesets.

## API keys

Do not commit real API keys to this repository.

For public browser examples, use a Mappinest API key with allowed-domain restrictions. For local testing,
allow `localhost` in the key policy or use a temporary development key.

## Documentation

- Mappinest docs: https://www.mappinest.com/docs
- Tiles API: https://www.mappinest.com/docs/tiles-api
- Maps API: https://www.mappinest.com/docs/maps-api
- Guides: https://www.mappinest.com/docs/guides
