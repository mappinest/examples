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
