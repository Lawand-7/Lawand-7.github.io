# LAWAND — Solar System

A luxurious interactive 3D solar system set in the Milky Way, built with [Three.js](https://threejs.org/).

**Live:** https://lawand-7.github.io/

## Features

- Glowing sun with additive bloom and animated corona
- All 8 planets with procedural surface textures, real orbital motion & spin
- Saturn's & Uranus' rings, and Earth's orbiting moon
- **Click a planet** → the camera flies to it and follows it, with a bilingual (EN / عربي) info card (diameter, distance, moons, year)
- **Asteroid belt** of 700 drifting rocks between Mars and Jupiter
- **Colored nebula clouds** in the deep background
- **A comet** that periodically streaks across the system with a glowing tail
- **Ambient space audio** — procedural drone with a mute/unmute button (no audio files)
- **Click Earth** to open a personal "About Lawand" section with skills & links
- Thousands of stars in a flattened galaxy disk (Milky Way band)
- Cinematic bloom post-processing
- Orbit controls — drag to rotate, scroll to zoom, hover to see a planet's name
- Zero build step — a single `index.html`, modules loaded from CDN
- Procedural textures only — no external image files

## Run locally

Open `index.html` in a browser, or serve it:

```bash
npx serve .
```
