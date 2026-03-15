# Hero Tower Defense

A browser-based MVP: you control a hero defending a base from waves of enemies. Move with arrow keys, auto-shoot when in range, collect coins from kills, and buy defense towers.

## Two versions

- **`index-phaser.html`** (recommended) – Built with **[Phaser 3](https://phaser.io)** (WebGL). Uses a proper game engine with tile-based terrain, particle effects (death bursts, coin pickups), and **sprite-based** hero and enemies (pixel-art by default). For a **more realistic look**, add your own art: see **`assets/ASSETS.md`** – put `hero.png` and `enemy.png` in the `assets/` folder (e.g. from [Kenney](https://kenney.nl) or [OpenGameArt](https://opengameart.org)) and the game will use them automatically.
- **`index.html`** – Original canvas-only version. Works fully offline; no dependencies.

## How to play

- **Arrow keys** – Move the hero
- **Auto-shoot** – Hero shoots arrows at the nearest enemy when in range
- **Coins** – Enemies drop coins when killed; walk near them to collect
- **Towers** – **Walk over** a build zone (dashed square) with 50+ coins to buy a tower
- **Levels** – More enemies per level; mix of grunts (1 HP), armored (3 HP), fast (2 HP)
- **Maps** – The map (path + tower slots) changes after each level (3 layouts rotate)

## Run locally

**Project location:** `/Users/b/vibe coding/hero-tower-defense/`

Open the Phaser version in a browser:

```bash
open "/Users/b/vibe coding/hero-tower-defense/index-phaser.html"
```

Or run a local server from the project folder:

```bash
cd "/Users/b/vibe coding/hero-tower-defense"
npx serve .
# then open http://localhost:3000 and click index-phaser.html
```

## Use as a separate GitHub project

To push this folder to its own GitHub repo:

```bash
cd "/Users/b/vibe coding/hero-tower-defense"
git init
git add .
git commit -m "Initial commit: Hero Tower Defense MVP"
git remote add origin https://github.com/YOUR_USERNAME/hero-tower-defense.git
git push -u origin main
```
