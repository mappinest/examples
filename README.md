# Mappinest Examples

Public examples for using Mappinest with common map clients.

Use this repo with the [Mappinest map client guides](https://www.mappinest.com/docs/guides). The standalone HTML examples match the JavaScript examples shown in the docs.

These examples show the three main integration paths:

- Maps API through StyleJSON URLs.
- Tiles API through TileJSON and direct XYZ tile URLs.
- Dataset API through authenticated GeoJSON URLs.

## Examples

| Map client | Examples |
| --- | --- |
| MapLibre GL JS | [Map style](examples/maplibre-gl-js/stylejson-map-style/index.html) · [Vector tiles](examples/maplibre-gl-js/uploaded-vector-tileset/index.html) · [Raster tiles](examples/maplibre-gl-js/uploaded-raster-tileset/index.html) · [GeoJSON dataset](examples/maplibre-gl-js/dataset-geojson/index.html) |
| Mapbox GL JS | [Map style](examples/mapbox-gl-js/stylejson-map-style/index.html) · [Vector tiles](examples/mapbox-gl-js/uploaded-vector-tileset/index.html) · [Raster tiles](examples/mapbox-gl-js/uploaded-raster-tileset/index.html) · [GeoJSON dataset](examples/mapbox-gl-js/dataset-geojson/index.html) |
| OpenLayers | [Map style](examples/openlayers/stylejson-map-style/index.html) · [Vector tiles](examples/openlayers/uploaded-vector-tileset/index.html) · [Raster tiles](examples/openlayers/uploaded-raster-tileset/index.html) · [GeoJSON dataset](examples/openlayers/dataset-geojson/index.html) |
| Leaflet | [Map style](examples/leaflet/stylejson-map-style/index.html) · [Vector tiles](examples/leaflet/uploaded-vector-tileset/index.html) · [VectorGrid](examples/leaflet/leaflet-vectorgrid/index.html) · [Raster tiles](examples/leaflet/uploaded-raster-tileset/index.html) · [GeoJSON dataset](examples/leaflet/dataset-geojson/index.html) |

## Run locally

Install dependencies:

```bash
npm install
```

Start the local preview server:

```bash
npm run dev
```

Open one of the example folders from the Vite local server. Get a free Mappinest API key from [API Keys & Access](https://www.mappinest.com/console/keys), then replace `YOUR_MAPPINEST_KEY`.

The examples use public Mappinest samples. `mappinest.COUNTIES` is a vector tileset, `mappinest.countries-raster` is a raster tileset, and `mappinest.world-cities` is a dataset. Any valid API key can read them, and requests count toward the usage of that key. Replace the sample IDs with your own tileset or Dataset IDs to load your data.

## API keys

Replace `YOUR_MAPPINEST_KEY` with your API key from the [Mappinest Console](https://www.mappinest.com/console/keys).
Restrict browser keys to your application's domains and include `localhost` when testing locally.

## Documentation

- Mappinest docs: https://www.mappinest.com/docs
- Tiles API: https://www.mappinest.com/docs/tiles-api
- Maps API: https://www.mappinest.com/docs/maps-api
- Dataset API: https://www.mappinest.com/docs/dataset-api
- Guides: https://www.mappinest.com/docs/guides
