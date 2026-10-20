# Examples

Each example is intentionally small. It loads public Mappinest samples, so it runs as soon as you add your API key.

Replace `YOUR_MAPPINEST_KEY` with a free API key from API Keys & Access.

To load your own data, replace:

- `mappinest.COUNTIES` or `mappinest.countries-raster` with your tileset ID.
- `COUNTIES` with the source layer from your TileJSON `vector_layers`.
- `mappinest.world-cities` with your exact Dataset ID.
- `light` or `streets` with another available map style ID.

Leaflet does not support vector tiles natively, so the Tiles API examples use a [MapLibre bridge](https://www.mappinest.com/docs/guides/leaflet/uploaded-vector-tileset) or [Leaflet.VectorGrid](https://www.mappinest.com/docs/guides/leaflet/leaflet-vectorgrid).


Scopes are optional for read examples. If you set any scopes, include `tiles:read` for the Tiles API,
`maps:read` for the Maps API, and `datasets:read` for the Dataset API, depending on which APIs the
example uses.

Use the Mappinest documentation when you need endpoint details:

- https://www.mappinest.com/docs/tiles-api
- https://www.mappinest.com/docs/maps-api
- https://www.mappinest.com/docs/dataset-api
- https://www.mappinest.com/docs/guides
