# UI Concept — Minimal Liquid Glass

A minimal, liquid-glass UI concept for this SkinChanger, inspired by
Matcha's UI style.

**Mock data only.** This is a design prototype (`index.html`) — it is not
connected to `gui.lua` / `main.lua` and does not apply any changes in-game.

## View it

Open `index.html` in any modern browser. No build step, no dependencies —
all CSS and JS are inline.

Try:
- Search skins, filter by Primary / Secondary / Melee / Utility
- Click a skin row to preview it
- **Save & Apply** (simulated progress)
- Settings → change the accent colour live

## Design

- Frosted liquid-glass window (`backdrop-filter: blur + saturate`)
- Icon rail navigation
- Minimal skin list rows: thumbnail, name/weapon, selected check
- No rarity labels, badges, or extra panels — essentials only
