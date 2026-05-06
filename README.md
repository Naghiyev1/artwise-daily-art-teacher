# ArtWise v1.3.1

Image Reliability Fix.

## What changed

- Fixed bad Wikimedia URL pattern globally: `Special:FilePath:` → `Special:FilePath/`
- Replaced a batch of known problematic public-domain URLs with more reliable direct paths
- Added generated ArtWise note-card placeholders for copyrighted / unstable artworks where reliable direct public image files are not available
- Strengthened image fallback handling
- Preserved v1.3 curated library size: 393 artworks
- Updated cache to v1.3.1
- JavaScript syntax checked successfully

## Important note

Some famous modern works are copyrighted or unstable as direct public image URLs. For those, the app now shows a designed ArtWise note-card placeholder instead of a broken image. The explanation remains in the app.

## Upload

Upload all files to your repo root:

- index.html
- style-v1-3-1.css
- app-v1-3-1.js
- style.css
- app.js
- README.md
- icon.svg
- manifest.json
- service-worker.js
