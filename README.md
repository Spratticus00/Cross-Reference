# Cross Reference

A chess review board for annotating games: drag pieces, draw arrows and circles,
use live Stockfish annotations, and save positions as GIFs.

- `index.html` is the whole app (iPhone layout)
- Works offline after the first visit, and can be added to an iPhone home screen
  from Safari: Share, then Add to Home Screen.

## Optional: full-strength Stockfish 19

Works without this. For much stronger and faster analysis, upload these two files
next to the others (same top-level place, names unchanged):

- `stockfish-19-lite-single.js`
- `stockfish-19-lite-single.wasm`

Get them from the official Stockfish.js release (nmrugg/stockfish.js on GitHub,
version 19) or the npm package `stockfish@19.0.1` (in its `bin` folder). The app
finds them automatically; otherwise it uses an online build.

Chess engine: Stockfish (GPL v3), loaded from a public CDN, or from the two optional files above.
