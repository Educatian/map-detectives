# Map Detectives — playable browser prototype

Teach an AI to read the land from the sky, then take it somewhere it has never been.
A Unity WebGL build (about 15 MB). Desktop Chrome or Edge recommended.

## Pitch video (2 minutes)
[![Map Detectives pitch video](https://img.youtube.com/vi/lTcpLAkgCcE/maxresdefault.jpg)](https://youtu.be/lTcpLAkgCcE)

▶ https://youtu.be/lTcpLAkgCcE

Built by the ADIE Lab, The University of Alabama. Imagery: USDA NAIP via USGS The National Map (public domain).
Buildings and places © OpenStreetMap contributors (ODbL).

## Publish with GitHub Pages
1. Create a new public repository (for example `map-detectives`).
2. Upload everything in this folder (index.html, .nojekyll, Build/, README.md) to the main branch.
3. Settings → Pages → Build and deployment → Source: "Deploy from a branch", Branch: `main` / `(root)` → Save.
4. After about a minute the game is live at `https://<your-account>.github.io/map-detectives/`.

The build uses Brotli-compressed files with Unity's decompression fallback, so it runs on GitHub Pages without server configuration.
