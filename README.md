# Project 2084 — Robotron HTML5 Tribute

A twin-stick arena shooter homage to the classic Robotron: 2084, built as a single HTML5 file with Canvas 2D, Web Audio API, and Gamepad API support.

**[Play it here](https://nwfella.github.io/project-2084/)**

## Features

- **Independent 8-way movement & firing** — WASD to move, Arrow keys to fire (or Gamepad left/right sticks)
- **11 enemy types** — Grunts, Hulks, Brains, Progs, Spheroids, Enforcers, Quarks, Tanks, and more
- **Human rescue meta-game** — Escalate your rescue streak for up to 5,000 pts per human
- **Wave progression** — 9+ distinct wave types that cycle and scale with +2% speed per wave
- **CRT visual overlay** — Scanlines, vignette, and phosphor bloom effects
- **Web Audio API synthesis** — Procedural sound effects (square/saw/noise) with 8-channel audio choking
- **Gamepad API** — Left stick move, right stick fire (auto 8-way snapping)
- **No dependencies** — Single HTML file, zero frameworks

## Controls

| Action | Keyboard | Gamepad |
|--------|----------|---------|
| Move | W A S D | Left stick / D-pad |
| Fire | Arrow keys | Right stick |
| Start | Click / Space / Enter | Any button |

## Tech Stack

- **Rendering**: HTML5 Canvas 2D with `image-rendering: pixelated`
- **Audio**: Web Audio API with oscillator synthesis (no audio files)
- **Input**: Keyboard + Gamepad API
- **CRT effects**: Canvas 2D overlays (scanlines, vignette, bloom)
- **Hosting**: GitHub Pages

## Build

No build step. Open `index.html` in any modern browser.

## License

MIT
