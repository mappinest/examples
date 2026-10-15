# Examples

Each example is intentionally small and uses placeholder values.

Replace:

- `YOUR_MAPPINEST_KEY` with a free Mappinest API key from API Keys & Access.
- `mappinest.COUNTIES` or `mappinest.countries-raster` with your own tileset Id when adapting the uploaded tileset examples.
- `COUNTIES` with the source layer from your TileJSON metadata when adapting the uploaded vector examples.
- `mappinest.world-cities` is the read-only sample used by the GeoJSON examples. Replace it with your exact Dataset ID when working with your own data.
- `light`, `streets`, or another map ID with an available Mappinest map style.

Leaflet does not support vector tiles natively, so the Tiles API examples use a [MapLibre bridge](https://www.mappinest.com/docs/guides/leaflet/uploaded-vector-tileset) or [Leaflet.VectorGrid](https://www.mappinest.com/docs/guides/leaflet/leaflet-vectorgrid).


Scopes are optional for read examples. If you set any scopes, include `tiles:read` for the Tiles API,
`maps:read` for the Maps API, and `datasets:read` for the Dataset API, depending on which APIs the
example uses.

Use the Mappinest documentation when you need endpoint details:

- https://www.mappinest.com/docs/tiles-api
- https://www.mappinest.com/docs/maps-api
- https://www.mappinest.com/docs/dataset-api
- https://www.mappinest.com/docs/guides
