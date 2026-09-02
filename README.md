# chessnotate.github.io

Marketing site for ChessNotate, an iOS app for capturing a chess game from a scoresheet as a 
validated PGN.

- `index.html` / `style.css` — the landing page
- `img/` — logo, screenshots, App Store / web-app badges
- `fonts/` — Fraunces (wordmark only), bundled with its SIL OFL license per the license's redistribution requirement
- `web/` — hosted build of the free/lite web version (once added)

Served via GitHub Pages.

## Updating web/

No automated build/sync yet. Before publishing, manually confirm the
files in `web/` were built from the commit you intend to ship (check the
main repo's commit hash the build came from) and replace the whole
directory rather than patching individual files, so stale assets from a
previous build don't linger.
