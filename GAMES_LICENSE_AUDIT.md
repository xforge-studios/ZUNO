# ZUNO embedded game integration — licence register

This package embeds 20 games in a ZUNO iframe player, loading them from their existing Libre Arcade publisher-hosted pages. It does not copy game files into ZUNO. The original authors and licensors retain their rights. This is an integration prototype, not a direct publishing agreement with each upstream author.

| Game | Publisher-hosted page | Reported licence / notes |
|---|---|---|
| Klondike | [Play](https://linkingtechnologies.github.io/libre-arcade/klondike/public/index.html) | MIT engine/solver; CC0 card deck |
| Netris | [Play](https://linkingtechnologies.github.io/libre-arcade/netris/public/index.html) | GPL-2.0-or-later |
| Hextris | [Play](https://linkingtechnologies.github.io/libre-arcade/hextris/public/index.html) | GPL-3.0-only |
| HexGL | [Play](https://linkingtechnologies.github.io/libre-arcade/hexgl/public/index.html) | MIT; see provenance notes for asset exceptions |
| Same Game Gravity | [Play](https://linkingtechnologies.github.io/libre-arcade/same-game-gravity/public/index.html) | GPL-3.0-only |
| HTML5 Breakout | [Play](https://linkingtechnologies.github.io/libre-arcade/html5-breakout/public/index.html) | MIT |
| Elemental One | [Play](https://linkingtechnologies.github.io/libre-arcade/elemental-one/public/index.html) | MIT; replacement font/sound noted |
| HTML5 Snake | [Play](https://linkingtechnologies.github.io/libre-arcade/html5-snake/public/index.html) | MIT |
| Space Invaders | [Play](https://linkingtechnologies.github.io/libre-arcade/html5-space-invaders/public/index.html) | MIT |
| Strider | [Play](https://linkingtechnologies.github.io/libre-arcade/strider/public/index.html) | MIT; see unresolved provenance notes |
| Trapped | [Play](https://linkingtechnologies.github.io/libre-arcade/trapped/public/index.html) | MIT |
| Heal'em All | [Play](https://linkingtechnologies.github.io/libre-arcade/heal-em-all/public/index.html) | GPL-3.0 code; CC BY 4.0 graphics |
| The Lost Path | [Play](https://linkingtechnologies.github.io/libre-arcade/the-lost-path/public/index.html) | MIT |
| Netrok 0.95 | [Play](https://linkingtechnologies.github.io/libre-arcade/netrok/index.html) | GPL-2.0-or-later |
| Njam 1.21 | [Play](https://linkingtechnologies.github.io/libre-arcade/njam/index.html) | GPL-2.0-or-later source; GPL-3.0-or-later browser port |
| Naval Battle | [Play](https://linkingtechnologies.github.io/libre-arcade/naval-battle/index.html) | GPLv3 |
| For Science! | [Play](https://linkingtechnologies.github.io/libre-arcade/for-science/public/index.html) | GPL-3.0-or-later; third-party notices |
| 54321 | [Play](https://linkingtechnologies.github.io/libre-arcade/54321/public/index.html) | Historical custom non-exclusive grant; read provenance |
| Donkey Bolonkey | [Play](https://linkingtechnologies.github.io/libre-arcade/donkey-bolonkey/public/index.html) | GPL-2.0-or-later |
| PSY PONG 3D | [Play](https://linkingtechnologies.github.io/libre-arcade/psypong3d/public/index.html) | GPL-3.0-or-later |

## Important
- Libre Arcade describes itself as a collection of browser restorations and ports, with provenance and licensing recorded per game. The repository root is GPL-3.0; individual games may retain other licences.
- Read each individual game's `LICENSE`, `CREDITS.md`, `THIRD_PARTY_NOTICES.md`, and provenance notes before copying, self-hosting, modifying, or monetizing it.
- Some games have special asset exceptions or provenance caveats; these are noted above.
- The iframe may be blocked by publisher-side `X-Frame-Options` or Content Security Policy. If blocked, the player provides an “Open separately” fallback. A site owner cannot bypass those protections from frontend code.
- This package does not prove all frames have been tested in the user's production domain. Verify every title after deploying.


## Additional collection link
- **Arcade 100** — publisher-hosted collection of 100 zero-dependency HTML5 games; MIT repository license is listed by its GitHub repository. ZUNO links to the collection homepage and does not redistribute or iframe individual game files. https://github.com/NnopponS/100-games and https://nnoppons.github.io/100-games/
