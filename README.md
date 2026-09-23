# Tic Tac Toe (Offline)

A single-file, fully offline Tic-Tac-Toe game — no build step, no server, no internet required.

## Run it
Just open `index.html` in any modern browser (double-click it, or drag it into a browser tab).

## Features
- Home screen, mode select, player setup, game board, result modal, settings, statistics, and how-to-play screens
- One vs One and Player vs Computer (Easy / Medium / Hard via Minimax with alpha-beta pruning)
- Hint system (3 per game, highlights a strong move without placing it)
- Sound effects generated with the Web Audio API (no audio files needed) — master/music/move/win toggles + volume slider
- Light / Dark / System theme, animation toggle, vibration toggle, timer toggle
- Win-streak, win-percentage and per-game statistics saved to localStorage
- Confetti on a human win, responsive layout for mobile/tablet/desktop

## Notes
Everything (HTML, CSS, JS) lives in `index.html` — the `css/` and `js/` folders are left empty on purpose (the suggested project layout, kept for reference) since the whole game runs as one self-contained file with zero dependencies, exactly to guarantee it works fully offline.
