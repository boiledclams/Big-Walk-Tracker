# Big Walk Puzzle Tracker

Mobile-first tracker for Big Walk puzzle progress.

## Images

The tracker no longer embeds or proxies images. Each puzzle has a **View image** link that opens the image URL directly in a new browser tab. The separate **Walkthrough** link opens the guide page.

This avoids image redirects being handled by the tracker itself. The image host may still redirect or block direct viewing if that host does not permit hotlinking; in that case, the tracker is not involved in the redirect.

## GitHub Pages

Upload the contents of this folder to the root of your repository with `index.html` at the root, then enable GitHub Pages from the `main` branch and `/(root)`.
