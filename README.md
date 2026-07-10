# rustify-music.github.io

GitHub Pages site hosting Android App Links verification for [Rustify](https://github.com/rustify-music), a Spotify client for Android.

## Files

- **`.well-known/assetlinks.json`** — Declares `com.varuna.rustify` as the verified handler for `https://rustify-music.github.io/r/...` wrapper links. Contains SHA256 fingerprints for both debug and release signing keys.
- **`.nojekyll`** — Tells GitHub Pages to serve the `.well-known` directory as-is.

The only functional file is the asset links JSON; there is no website here.
