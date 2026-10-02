# The Last Tab

A browser-based roguelite for the browser, built with plain HTML, CSS, and JavaScript.

Slogan: "Don't close the last tab."

## Overview

The player is trapped inside an infected internet. Each website is a room. Each tab is a burden. Every path consumes RAM, and if the browser overflows, the run ends.

This MVP includes:

- website-room flow
- command cards
- enemies and bosses
- single-route map with procedural shuffle
- meta progression and localStorage save
- daily challenge seed
- post-mortem report output

## How to run

1. Open `index.html` in a browser.
2. Press "New Run" to start.
3. Use the cards to fight threats and manage RAM.

## Files

- `index.html` - app shell and screen structure
- `styles.css` - browser-inspired interface
- `game.js` - game systems, route generation, combat, and save logic

## Controls

- Open Tab: adds a room to the active tab stack, costing RAM and granting a bonus.
- Close Tab: frees memory but removes the benefit.
- Continue: moves to the next site.
- Command cards: use them during encounters to attack, defend, clear status effects, and steal enemy abilities.

## Notes

- The game is intentionally deterministic and runs without AI.
- Daily challenge is generated from the current date and stored with progress.
- Saves are stored in `localStorage` to keep progression between runs.

## Future upgrades

- More website types and boss variants
- More route generation patterns
- A leaderboard with a shared daily seed
- More refined enemy logic and shop interactions
- Pixel-art browser theming and richer visual polish
