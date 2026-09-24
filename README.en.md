# NIGHTFURY

[简体中文](README.md) | **English**

This repository contains the deployable game release snapshot.

Browser arcade racing with seven selectable maps (including the partial Frog Kingdom preview), two supercars, drifting, nitro, loops and jumps.

**[Play](https://ziang-chen.github.io/nightfury-racing/?lang=en) · [Artwork](https://ziang-chen.github.io/nightfury-racing/design.html?lang=en)**

## Current game captures

4K real-time game captures with a free camera and hidden UI; original game materials and lighting.

![Canyon town · layered district](dist/screenshots/canyon-town-overview-4k.png)

![Canyon town · streets](dist/screenshots/canyon-town-street-4k.png)

![Pinball · layered core tower](dist/screenshots/pinball-layered-tower-4k.png)

![Pinball · metal tracks](dist/screenshots/pinball-metal-tracks-4k.png)


## Play

- **PC:** keyboard controls. **Phones and tablets:** left steering stick and right action buttons; landscape recommended.
- Select **1–5 laps** and **Easy / Normal / Hard** on the track selection screen. Defaults: **2 laps, Normal**.
- Switch English / 中文 from the main menu or pause screen. Pause to resume, restart or choose another track.
- The first car load shows download progress. Music, sound, graphics and mobile auto throttle can be adjusted in Settings.

| Action | Keyboard |
| --- | --- |
| Accelerate / Brake and reverse | W / S or ↑ / ↓ |
| Steer | A / D or ← / → |
| Drift / Air flip | Space |
| Nitro | Shift |
| Camera / Reset to road | C / R |
| Pause / Mute effects | Esc / M |

## Run locally

Requires Python 3:

```sh
python3 -m http.server 8768 --directory dist
```

Open [localhost:8768](http://localhost:8768/).

## License

Original code: [MIT](LICENSE). Car models: CC BY 4.0. Third-party credits, sources and licenses: [notices](THIRD_PARTY_NOTICES.md) · [credits](https://ziang-chen.github.io/nightfury-racing/credits.html?lang=en).

## Available maps

The links below open the current game with the selected map. Frog Kingdom is a partial geometry preview, not a finished map.

- [Neon City](https://ziang-chen.github.io/nightfury-racing/?map=0&lang=en) — Rainy neon streets.
- [Lava Volcano](https://ziang-chen.github.io/nightfury-racing/?map=1&lang=en) — Lava and volcanic roads.
- [Jade Rainforest](https://ziang-chen.github.io/nightfury-racing/?map=2&lang=en) — Canopy waterways and a giant-tree temple.
- [Frog Kingdom · Preview](https://ziang-chen.github.io/nightfury-racing/?map=3&lang=en) — Partial geometry preview; still in development.
- [Canyon Leap · New version](https://ziang-chen.github.io/nightfury-racing/?map=5&lang=en) — The rebuilt red-rock canyon.
- [Starlight Realm](https://ziang-chen.github.io/nightfury-racing/?map=7&lang=en) — Star bridges and intertwined loops.
- [Neon Pinball](https://ziang-chen.github.io/nightfury-racing/?map=9&lang=en) — A violet cyberpunk pinball circuit.


Map covers are AI concept artwork, not game captures. Older screenshots and artwork for unavailable maps remain in the [art gallery](https://ziang-chen.github.io/nightfury-racing/design.html?lang=en) and [historical captures](https://ziang-chen.github.io/nightfury-racing/screenshots/?lang=en#archive), separately labeled.
