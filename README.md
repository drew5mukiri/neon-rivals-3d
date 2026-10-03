# Neon Rivals: Arena 3D

A playable browser arena shooter with a neon sci-fi aesthetic, improved enemy AI, multiple arena maps, and a start menu.

## Features

- 3D arena combat using Three.js
- Four weapon classes: Pistol, SMG, Shotgun, Railgun
- Sound effects generated with Web Audio
- Dash and energy blast ability
- Enemy waves and boss rounds
- Multiple maps: Gridline, Gates, Rift
- Start menu and game loop flow
- Better enemy movement with strafing and boss behavior
- Coins, pickups, combo scoring, and shop upgrades

## Run locally

Because this project uses CDN-loaded Three.js, a local web server is recommended.

```bash
cd neon-rivals-3d
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Controls

- WASD: Move
- Mouse: Aim
- Click: Fire
- 1/2/3/4: Switch weapons
- Space: Dash
- E: Energy blast
- R: Reload
- B: Shop
- P: Pause
- Enter: Restart after defeat

## Notes

This version is intentionally lightweight and runs directly in a browser without needing npm install or a build tool.
