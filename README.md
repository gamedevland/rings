# Rings 3D

Playable web build for [GameDev.Land](https://gamedev.land/games/rings).

- Play: https://gamedevland.github.io/rings/
- Platform: web; no Poki SDK script is loaded.
- Campaign: 100 spatial levels, portrait and landscape layouts.
- Source revision: `470b20705d0fee4cdabacc26b9e6ef2bdc9ee286`.
- Release: 2026-11-10. Replaces the previous Rings build.

Three.js renders the puzzle into a texture displayed by PixiJS together with its UI.
Includes the two-step tutorial, spiral entrances, accelerating releases, confetti and fireworks.

This public repository contains the compiled game and bundled assets.
`build-info.json` records the source revision and hashes of every generated file.
GitHub Pages publishes the root of `main`; `.nojekyll` preserves the static bundle.
