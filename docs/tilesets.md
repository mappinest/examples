# Tilesets

Uploaded tilesets are usually referenced by tileset Id.

Example:

```txt
username.COUNTIES
```

For vector tiles, you also need the source layer name used inside the tileset.

Example:

```txt
COUNTIES
```

When you are not sure which source layer to use, fetch the TileJSON document and inspect
the `vector_layers` array.

```bash
curl "https://api.mappinest.com/v1/tiles/username.COUNTIES.json?key=YOUR_MAPPINEST_KEY"
```
