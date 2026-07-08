# API Keys

Mappinest examples define `const apiKey = 'YOUR_MAPPINEST_KEY';` and interpolate it into
StyleJSON, TileJSON, and tile URLs.

For browser examples:

- Use a development API key while testing locally.
- Restrict production keys by allowed domain.
- Do not commit real keys to this repository.
- Rotate a key if it was pasted into an issue, pull request, or public commit.

Common local origins:

```txt
http://localhost:5173
http://127.0.0.1:5173
```
