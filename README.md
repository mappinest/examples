# Mappinest Examples

Public examples for using Mappinest with common map clients.

Use this repo with the [Mappinest map client guides](https://www.mappinest.com/docs/guides). The standalone HTML examples match the JavaScript examples shown in the docs.

These examples show the three main integration paths:

- Maps API through StyleJSON URLs.
- Tiles API through TileJSON and direct XYZ tile URLs.
- Dataset API through authenticated GeoJSON URLs.

## Examples

| Map client | Example | Path |
| --- | --- | --- |
| MapLibre GL JS | Load map style | `examples/maplibre-gl-js/stylejson-map-style` |
| MapLibre GL JS | Uploaded vector tileset | `examples/maplibre-gl-js/uploaded-vector-tileset` |
| MapLibre GL JS | Uploaded raster tileset | `examples/maplibre-gl-js/uploaded-raster-tileset` |
| MapLibre GL JS | Editable GeoJSON Dataset | `examples/maplibre-gl-js/dataset-geojson` |
| Mapbox GL JS | Load map style | `examples/mapbox-gl-js/stylejson-map-style` |
| Mapbox GL JS | Uploaded vector tileset | `examples/mapbox-gl-js/uploaded-vector-tileset` |
| Mapbox GL JS | Uploaded raster tileset | `examples/mapbox-gl-js/uploaded-raster-tileset` |
| Mapbox GL JS | Editable GeoJSON Dataset | `examples/mapbox-gl-js/dataset-geojson` |
| OpenLayers | Load map style | `examples/openlayers/stylejson-map-style` |
| OpenLayers | Uploaded vector tileset | `examples/openlayers/uploaded-vector-tileset` |
| OpenLayers | Uploaded raster tileset | `examples/openlayers/uploaded-raster-tileset` |
| OpenLayers | Editable GeoJSON Dataset | `examples/openlayers/dataset-geojson` |
| Leaflet | Load map style | `examples/leaflet/stylejson-map-style` |
| Leaflet | Uploaded vector tileset | `examples/leaflet/uploaded-vector-tileset` |
| Leaflet | Leaflet.VectorGrid vector tileset | `examples/leaflet/leaflet-vectorgrid` |
| Leaflet | Uploaded raster tileset | `examples/leaflet/uploaded-raster-tileset` |
| Leaflet | Editable GeoJSON Dataset | `examples/leaflet/dataset-geojson` |

## Run locally

Install dependencies:

```bash
npm install
```

Start the local preview server:

```bash
npm run dev
```

Open one of the example folders from the Vite local server. Get a free Mappinest API key from [API Keys & Access](https://www.mappinest.com/console/keys),
then replace `YOUR_MAPPINEST_KEY`.
The uploaded vector examples use `mappinest.COUNTIES`, and the uploaded raster examples use
`mappinest.countries-raster` as sample tilesets. Dataset examples use
`mappinest.world-cities` as the read-only sample. Replace it with the exact Dataset ID from
your console when working with your own data.

## API keys

Replace `YOUR_MAPPINEST_KEY` with your API key from the [Mappinest Console](https://www.mappinest.com/console/keys).
Restrict browser keys to your application's domains and include `localhost` when testing locally.

## Documentation

- Mappinest docs: https://www.mappinest.com/docs
- Tiles API: https://www.mappinest.com/docs/tiles-api
- Maps API: https://www.mappinest.com/docs/maps-api
- Dataset API: https://www.mappinest.com/docs/dataset-api
- Guides: https://www.mappinest.com/docs/guides
