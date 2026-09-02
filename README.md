# chessnotate.github.io

Marketing site for ChessNotate, an iOS app for capturing a chess game from a scoresheet as a 
validated PGN.

- `index.html` / `style.css` — the landing page
- `img/` — logo, screenshots, App Store / web-app badges
- `fonts/` — Fraunces (wordmark only), bundled with its SIL OFL license per the license's redistribution requirement
- `webapp/` — hosted build of the free/lite web version (once added)

Served via GitHub Pages.

## Updating webapp/

No automated build/sync yet — there isn't even a web export script in the
main app repo as of this writing. Before publishing, manually confirm the
files in `webapp/` were built from the commit you intend to ship (check the
main repo's commit hash the build came from) and replace the whole
directory rather than patching individual files, so stale assets from a
previous build don't linger.
