# Neon Rivals: Arena 3D

A playable browser arena shooter rebuilt in 3D with a stylized neon sci-fi aesthetic.

## Features

- 3D arena combat using Three.js
- Four weapon classes: Pistol, SMG, Shotgun, Railgun
- Sound effects generated with Web Audio
- Dash and area blast ability
- Enemy waves and boss rounds
- Coins, pickups, combo scoring, shop upgrades
- No build step required

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

This is intentionally lightweight and designed to run directly in a browser without installing dependencies.
