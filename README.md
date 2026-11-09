# Hopscotch Highway

**Hop the endless highway: roads, rivers, rails and a hawk that hates waiting. Four lands, 32 stages, 25 hoppers.**

<p align="center">
  <img src="assets/screenshot-title.png" alt="Hopscotch Highway — title screen" width="820">
</p>

<p align="center">
  <a href="https://ai-llm-2030.github.io/TrueMarch_Games_Hopscotch_Highway/"><b>▶ Play Hopscotch Highway in your browser</b></a>
</p>

## Gameplay

<p align="center">
  <img src="assets/screenshot-play.png" alt="Hopscotch Highway — gameplay" width="820">
</p>

## Controls

| Keys | Action |
|---|---|
| ↑ ← ↓ → or W A S D | Hop |
| Space | Hop forward |
| Esc / P | Pause |
| M | Sound on / off |

## Run it yourself

No install, no build step, no server code, no network. The game runs entirely in your browser and keeps your progress in the browser's local storage.

```bash
git clone https://github.com/ai-llm-2030/TrueMarch_Games_Hopscotch_Highway.git
cd TrueMarch_Games_Hopscotch_Highway
python3 -m http.server 8000
# open http://localhost:8000
```

Opening `index.html` directly works too in most browsers; a local server is the most reliable way.

## What's inside

```
TrueMarch_Games_Hopscotch_Highway/
├── index.html        the whole game: one file, plain JavaScript and <canvas>
├── lib/
│   ├── arcade.js     shared helpers: crisp canvas, frame loop, input, theme
│   └── arcade.css    shared look
├── assets/           the pictures in this README
├── LICENSE
└── README.md
```

Written from scratch in vanilla JavaScript: every sprite, background and sound is drawn or synthesised in code (Canvas 2D and the Web Audio API). No libraries, no frameworks, no third-party assets.

## About

**Hopscotch Highway** is one of the 120+ games made by **[TrueMarch](https://truemarch.com)**. This repository is the standalone single-player edition of the game.

## License

© 2026 TrueMarch. All rights reserved. The source is published so you can read it, learn from it and play the game; see [LICENSE](LICENSE).
