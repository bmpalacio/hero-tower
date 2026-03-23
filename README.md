# Hero Tower Defense

Browser game: move a hero, defend your base, survive **10 levels**. Arrow keys (or tap on mobile), auto-shoot, coins from kills, **towers** and (from level 6) **walls** on enemy paths.

## Files in this repo

| File | Purpose |
|------|--------|
| **`index.html`** | Entry point for **GitHub Pages** — redirects to the Phaser build. |
| **`index-phaser.html`** | The game ([Phaser 3](https://phaser.io)). |
| **`assets/`** | Optional `hero.png` / `enemy.png` — see **`assets/ASSETS.md`**. |

Everything else is optional documentation; there is no second engine build in this repo.

## How to play

- **Move** – Arrow keys or tap to move
- **Shoot** – Nearest enemy in range
- **Coins** – Walk over drops to collect
- **Towers** – Stand on a dashed build zone with **50** coins to fund a tower
- **Walls** – From **level 6**, brown pads on lanes cost **100** coins and block enemies until destroyed
- **Levels** – Map layout can flip each level; difficulty ramps up

## Run locally

Open `index.html` or `index-phaser.html` in a browser, or from the project folder:

```bash
npx serve .
# open http://localhost:3000
```

## Optional art

Add **`assets/hero.png`** and **`assets/enemy.png`** for custom sprites — see **`assets/ASSETS.md`**.
