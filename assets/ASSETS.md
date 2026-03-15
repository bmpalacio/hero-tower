# Realistic art (optional)

The game runs with built-in pixel-art sprites. To use **realistic or high-quality art** instead:

1. **Download a free asset pack** (CC0 or similar):
   - [Kenney – Tiny Town](https://kenney.nl/assets/tiny-town) – top-down tiles and characters
   - [Kenney – RPG Urban Pack](https://kenney.nl/assets/rpg-urban-pack) – characters and tiles
   - [OpenGameArt](https://opengameart.org) – search for "top-down character" or "tower defense"

2. **Add these files into this `assets/` folder:**
   - **`hero.png`** – your hero / rider (e.g. knight on horse). Suggested size: 64×64 or 128×128 px.
   - **`enemy.png`** – enemy soldier/unit. Suggested size: 32×32 or 64×64 px.

3. **Reload the game** (refresh the browser). The game will load `hero.png` and `enemy.png` from this folder and use them instead of the built-in sprites.

No code changes needed. If the files are missing or invalid, the game falls back to the built-in art.
