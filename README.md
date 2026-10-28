# WARDROBE — Spatial Archive

A clean white spatial wardrobe gallery prototype. No external libraries or server required.

## Open locally
Double-click `index.html` in a modern browser.

## Publish on GitHub Pages
1. Create a public GitHub repository.
2. Upload `index.html`, `style.css`, and `script.js` to its root.
3. In repository **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
4. Wait for GitHub Pages to show the site URL.

## Features
- 80 generated demo silhouettes, plus your own image-based items.
- Mouse drag to orbit, scroll to zoom; Explore mode pans, and WASD/arrows pan the scene.
- Category filtering, search, spatial regrouping by category/color/decade/brand.
- Optional floating motion and labels.
- Item detail panel and add/delete personal items.
- Export/import your personal archive as JSON.

## Important limitations
- This is a **2.5D prototype**: flat image cards are positioned in 3D and face the viewer. It is not a 3D clothing mesh viewer.
- Data is stored only in the current browser's localStorage, not on GitHub or across devices. Use **EXPORT ARCHIVE** regularly. Clearing browser storage can erase the collection.
- A public GitHub Pages site is visible to others. This prototype does **not** have password protection or cloud sync.
- Background removal is not automatic; upload PNG/WebP with transparent background for the cleanest result.
- The 80 demo items are placeholders and are not included in JSON exports.
