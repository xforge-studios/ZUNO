# ZUNO — XFORGE STUDIOS

A responsive browser-games portal for desktop and mobile.

## Included
- 35 third-party browser game links hosted by Libre Arcade.
- Arcade 100 external collection link (opens on the publisher's site).
- Search and category filters.
- In-page iframe player, fullscreen and publisher-site fallback.
- ZUNO 192px/512px app icons, PWA manifest and basic service worker.
- XFORGE STUDIOS branding.

## Publish
Upload the contents of this folder to the root of a GitHub Pages repository, or any static hosting provider. No build step is required.

## Important rights and compatibility note
ZUNO links to third-party hosted games; it does not bundle or claim ownership of their code or artwork. Licences and asset provenance vary by game; see `GAMES_LICENSE_AUDIT.md`. Check each game's licence and notices before copying, modifying, redistributing or monetising it. Some hosts may block iframe embedding; use the publisher-site fallback.

## Game icon handling
The Hextris tile uses its original developer press-kit logo. Other game tiles try to load a favicon from the corresponding publisher game page; where a publisher does not provide one, the tile falls back to a compact text mark rather than inventing an official logo. Some publisher pages may block embedding or may not expose a favicon.

## Mega Arcade collection (142 additional games)
ZUNO includes an in-page launcher for the separately hosted `sausi-7.github.io/games/` catalogue, described by its publisher as 142 playable browser games across 10 categories. These titles remain hosted and maintained by that third-party project; they are not copied into this ZUNO package. The launcher offers an iframe view and an external-site fallback. Embedding can be blocked by the publisher's browser security headers.
