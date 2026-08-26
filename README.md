# HOLO · ELEMENTS — Interactive Periodic Table

A single-file, zero-dependency interactive periodic table with holographic atom projections.

**Try it:** open `index.html` in any browser — no build, no server, no internet required.

## What it does

- **All 118 elements** in a dark, neon, category-coded layout
- **Tap any element** → a hologram of its atom materializes over a projector base:
  glitchy spawn animation, glowing nucleus, electron shells as tilted 3D rings
  orbiting at different speeds, the whole atom slowly rotating — tinted in the
  element's family color
- **Learn why it sits where it sits** — every element has a hand-written fact
  (what it is) plus a generated explanation of its group, period, electron
  shells, and what that means chemically
- **States of matter** — solid / liquid / gas at 25°C on every card, with an
  All / Solid / Liquid / Gas filter
- **Quiz mode** — 10-question rounds (find by name, symbol, number, or family),
  score + streak tracking, sounds, and a reward hologram for correct answers
- **Search** by name, symbol, or atomic number; legend chips spotlight a family
- **Synthesized sound effects** (Web Audio, no audio files) with a mute toggle
- Works with mouse and touch, keyboard navigation (←/→/Esc)

## Notes

- Electron shell data is verified: every element's shells sum exactly to its
  atomic number (Palladium's famous empty-5th-shell exception included).
- Everything — data, styles, logic, sounds — lives in the one HTML file.

## Live demo

Hosted on GitHub Pages: `https://<user>.github.io/holo-elements/`
