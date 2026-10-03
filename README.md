# Shadow Blades

A 2D ninja fighting game in a single HTML file — no build step, no assets. Everything is drawn with the Canvas API and the sound effects are synthesized with Web Audio.

A stages game: battle through **38 stages**, each set in its own endless, looping Japanese temple town with its own weather, using 15 ninja weapons. Every 5th stage is a boss. Clear a stage to unlock the next and earn up to 3 stars (based on health left). Progress saves in your browser.

## Play

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 5210
```

## Controls

| Action | Keys |
|---|---|
| Move | A / D (or ← →) |
| Jump | W (or ↑, Space) |
| Attack | J |
| Block | K |
| Special (when meter is full) | L |
| Weapons | 1–9, 0, R, T, Y, U, I — or Q / E to cycle, or click a slot |
| Mute | M |
| Back to stage map | Esc |

On the stage map, use the arrows / WASD and Enter (or tap a stage, then tap again). Touch screens get on-screen buttons.

## Weapons

Katana · Nunchaku · Bo Staff · Kusarigama · Shuriken · Sai · Tonfa · Naginata · Tekko-kagi · Fukiya · Kunai · Twin Kama · Tessen · Kanabo · Yumi Bow — each with its own special move.
