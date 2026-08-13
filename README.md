# Sphere Circles

Animated tangential circles on a sphere — desktop playground + phone screensaver.

## Live

- Desktop: https://azzabazza11.github.io/sphere-circles/
- Screensaver: https://azzabazza11.github.io/sphere-circles/screensaver.html?v=1.3.8

## Local

```bash
python3 -m http.server 8080
```

Open http://localhost:8080/

## Features

- Circles grow from the equator, open full, then shrink on the other side (constant angular speed)
- Up to **108** circles, with detail auto-throttled at high counts
- **Fly** — altitude-scaled paths along tilting plane normals; bloom + helix peel into space
- **Mirror** — every other circle takes the reflected pathway; all ease home when Fly turns off
- **Vel by R** / **Inward** fly options, plus trails
- **Auto flow** — one slider wanders at a time (tap canvas to jump); Flow spd sets crawl rate
- Concertina control sections and fat, finger-friendly sliders
- Desktop presets (Lattice, Nebula, Launch, Helix, Wire, Dense)
- Look controls: glow, ghost, hue drift, pulse, fill, stars, orbit
- Quick **Fly** / **Flow** toggles
- Phone screensaver: fullscreen-friendly, pinch-zoom, wake lock, Controls FAB
- **Share** — QR + copy link for the current page, plus **Support on Ko-fi**
- Hard **Reload** clears service worker + caches so updates stick
