# Neon Dodge

A tiny neon arcade dodger — fly the ship, dodge falling neon, survive as long as you can.
Single-file, no build step: plain HTML + `<canvas>` + the WebAudio API, every visual and
sound generated in code.

**This repo is a dry-run** of an agentic planning→production workflow (temp name so the
real demo keeps the clean `neon-dodge` name).

## Play
Open `index.html` in a browser, or the live deploy. Move with mouse/touch or arrow keys;
`P` pauses, `M` mutes. High score is saved locally.

## Stack
- `index.html` — the whole game (gameplay, procedural art, synthesised SFX, UI)
- Hosted on **Vercel** (static), version-controlled on **GitHub**.
