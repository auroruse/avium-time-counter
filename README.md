# Avium Time Counter

Browser-based IC/OOC time converter built for the [Avium Cinematic Universe](https://github.com/auroruse/avium-football-engine) roleplay setting. Single-file vanilla app, zero dependencies.

**[Live App](https://auroruse.github.io/avium-time-counter/)**

## Features

### Live Clock
- Nixie tube display showing current in-character date and time
- Updates every IC second (~7 ticks per real-world second at 52 days/year)
- Day of week, full date, and HH:MM:SS readout

### Time Calculator
- Bidirectional OOC↔IC conversion
- GMT offset support for local timezone input
- Handles dates across epoch boundaries and timeskips

### Epoch System
- Code-editable `EPOCHS` array for timeskips and rate changes
- Each epoch defines an OOC anchor, IC anchor, days-per-year rate, and label
- Calculator and clock automatically resolve across all epochs

## Usage

Open `index.html` in a browser. No build step, no server, no dependencies.

## Deploy

Push to `main` — GitHub Pages serves `index.html` directly.

Repo Settings > Pages > Source > Deploy from a branch > `main` / `/ (root)`.
