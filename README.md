# Big Walk Puzzle Tracker — Stable Cleanup

This build removes all image/media data and UI, keeps the per-puzzle walkthrough links, and preserves the existing tracker features.

It also uses a network-first, versioned service worker (`v6`) registered with `updateViaCache: 'none'` so GitHub Pages updates should appear after a normal refresh without Ctrl+F5.

Upload the four files in this folder to the root of the `main` branch:
- index.html
- manifest.json
- sw.js
- README.md (optional)
