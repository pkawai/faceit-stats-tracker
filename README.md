# FACEIT CS2 Stats Tracker

A single-file HTML tool that displays your recent FACEIT CS2 match statistics with interactive charts and detailed performance breakdowns.

## Features (Planned)

1. **Match History Table** — Last 5-10 matches with W/L, map, score, K/D/A
2. **Player Stats Summary** — Overall K/D ratio, win rate, headshot %, avg kills
3. **ELO Progression Chart** — Line chart showing ELO over recent matches
4. **K/D Trend Chart** — Visualize performance trends across matches
5. **Map Breakdown** — Bar chart of maps played + win rate per map
6. **Best/Worst Match Highlight** — Auto-detect your best and worst game
7. **Dark/Light Mode Toggle** — Theme switch with localStorage persistence

## How to Use

1. Open `index.html` in your browser
2. Enter your FACEIT username
3. (Optional) Enter your FACEIT API key for live data — get one free at [developers.faceit.com](https://developers.faceit.com)
4. Click "Fetch Stats" to load your recent matches

Without an API key, the app loads sample data so you can explore all features.

## Setup

No installation needed — just open `index.html` in any modern browser.

```bash
git clone https://github.com/YOUR_USERNAME/faceit-stats-tracker.git
open index.html
```

## Tech Stack

- HTML / CSS / Vanilla JavaScript
- Chart.js (loaded via CDN) for data visualization
- FACEIT Data API v4
