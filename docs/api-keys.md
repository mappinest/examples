# API Keys

[Get an API key](https://www.mappinest.com/console/keys) in the [Mappinest Console](https://www.mappinest.com/console), then replace `YOUR_MAPPINEST_KEY` in the examples.

Mappinest examples define `const apiKey = 'YOUR_MAPPINEST_KEY';` and interpolate it into
StyleJSON, TileJSON, tile URLs, and Dataset GeoJSON URLs.

For browser examples:

- Use your default API key or create a separate API key for local testing.
- Restrict production keys by allowed domain.
- Scopes are optional for read examples. If you set any scopes, include the read scope for each API the example uses. Tiles API requires `tiles:read`, Maps API requires `maps:read`, and Dataset API requires `datasets:read`.
- Do not commit real keys to this repository.
- Rotate a key if it was pasted into an issue, pull request, or public commit.

Common local origins:

```txt
http://localhost:5173
http://127.0.0.1:5173
```
