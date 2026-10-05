# Marriage · Hisab Kitab

[Open the app](https://shrijesh.github.io/Marriage-Hisab-Kitab/)

A refined mobile-first scorekeeper for Nepali Marriage. No account needed; games stay in each player's browser.

- 2–8 players, direct maal entry and live scoring.
- Seen/Unseen status, configurable dublee rules and optional Better doubling.
- Round history, editing, undo, NPR totals and net-balance settlement.
- Backup export/import, dark mode and offline startup after an online visit.

Share the app link with friends. Sessions are local to each device; this is a scorekeeper, not a live multiplayer card game. Clearing browser data removes local sessions unless backed up.

## Installation

Android Chrome: Install app/Add to home screen. iPhone Safari: Share → Add to Home Screen. Installation options depend on the browser.

## Hosting and maintenance

GitHub Pages publishes `main`, repository root. No build or external runtime dependencies.

The deployed application is self-contained in `index.html`, including styles and JavaScript. JavaScript sections are labelled with their source-module names. `sw.js` caches the app for offline use; `manifest.webmanifest` defines installation metadata. Existing `app.js`, `js/` and `styles/` files are retained from the original fork and are not loaded by the standalone entry page.

For local use:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open http://127.0.0.1:8765.

## Rules and credit

House rules vary. The in-app Rules page explains implemented conventions and links to the scoring references. New games default to the original app's dublee-exemption convention; it can be changed before playing. Maal totals are entered manually.

Original developer: Saroj Poudyal. Original source: [cynicandroid/Marriage-Hisab-Kitab](https://github.com/cynicandroid/Marriage-Hisab-Kitab). Original project describes its licence as GNU General Public License. Entertainment scorekeeping only; no payments processed.
