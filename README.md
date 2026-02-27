# ⚔ Empires of the Age

A Civilization 6-inspired hex-based strategy game playable entirely in the browser — no dependencies, no install required.

## 🎮 How to Play

Open `index.html` in any modern browser and start conquering!

### Core Loop
1. **Select your Settler** → click **Found City** to establish your capital
2. **Build units** from your city's production queue
3. **Research technologies** from the bar at the bottom
4. **Expand** by founding more cities and claiming territory
5. **Destroy** all AI units and cities to win

### Controls
- **Click** a tile to select it
- **Click your unit** → use Move / Attack / Found City buttons in the right panel
- **Scroll** to pan the map
- **Middle-mouse drag** to pan freely
- **End Turn** button (top right) to advance the turn

## 🗺 Features

- **Hex grid map** — procedurally generated with 7 terrain types (Plains, Forest, Hills, Mountains, Desert, Tundra, Ocean)
- **Fog of War** — explore the map as your units move
- **City Building** — found cities, grow population, expand territory
- **Districts** — build Granary, Forge, Campus, Market, Barracks
- **6 Unit Types** — Settler, Warrior, Archer, Horseman, Swordsman, Catapult
- **Technology Tree** — 10 techs unlocking new units and buildings
- **AI Opponent** — builds cities, trains units, and attacks your civilization
- **Animated Graphics** — water shimmer, city glow, terrain textures, shield-style units

## 🏰 Terrain Types

| Terrain   | Food | Production | Science | Notes |
|-----------|------|-----------|---------|-------|
| Plains    | 2    | 1         | 0       | Best for early cities |
| Forest    | 1    | 2         | 1       | Good production |
| Hills     | 1    | 2         | 0       | Defensive bonus |
| Mountain  | 0    | 0         | 2       | Impassable |
| Desert    | 0    | 1         | 0       | Poor yields |
| Tundra    | 1    | 0         | 0       | Cold frontier |
| Ocean     | 0    | 0         | 0       | Impassable |

## ⚔ Unit Stats

| Unit       | HP | Attack | Defense | Move | Requires |
|------------|----|--------|---------|------|----------|
| Settler    | 50 | —      | 5       | 2    | —        |
| Warrior    | 80 | 20     | 15      | 2    | —        |
| Archer     | 60 | 25     | 10      | 2    | Archery  |
| Horseman   | 70 | 30     | 15      | 4    | Horseback Riding |
| Swordsman  | 90 | 35     | 20      | 2    | Iron Working |
| Catapult   | 50 | 40     | 5       | 2    | Mathematics |

## 🔬 Technology Tree

```
Pottery ──────────────► Writing ──► Mathematics
                                └──► Currency

Animal Husbandry ──────► Archery
                    └──► Horseback Riding

Mining ────────────────► Bronze Working ──► Iron Working
```

## 🛠 Tech Stack

- Pure HTML5 / CSS3 / Vanilla JavaScript
- Canvas API for rendering
- No frameworks, no build tools, no dependencies
- Single file — just open and play

## 📄 License

MIT — free to use, modify, and distribute.
