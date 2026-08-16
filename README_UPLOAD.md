# Bit 2048 Extreme store website

Upload every file and directory in this folder to the document root for
`https://bit2048.hopalt.com/`.

Required public URLs:

- `https://bit2048.hopalt.com/index.html`
- `https://bit2048.hopalt.com/privacy_policy_bit2048Extreame.html`
- `https://bit2048.hopalt.com/assets/icon.png`

Keep the `assets` directory structure unchanged so the homepage screenshots and
social preview image continue to resolve.

Google Play assets are maintained separately in:

- `docs/store/android/icons_extreme`
- `docs/store/android/feature_graphic_extreme`
- `docs/store/android/screenshots_extreme`

Regenerate the raster store assets with:

```sh
NODE_PATH=<path-to-node_modules> node tools/generate_store_assets.js
```
