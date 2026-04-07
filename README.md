# 🎮 Tank Battle

A two-player top-down tank combat game playable entirely in the browser — no installs, no dependencies, just open and fight.

## 🔗 [**🚀 Click Here to Play the Live Demo**](https://jingzhe0915.github.io/tank-battle/)



---

## ✨ Features

- **Local 2-player PvP** — both players share the same keyboard
- **Fully remappable controls** — rebind any key or mouse button for either player
- **Custom tank colors** — pick your own color via the color picker
- **Power-up system** — 6 unique power-ups that spawn dynamically during the match
- **Wall physics** — bullets bounce off walls and decay over time
- **Particle effects** — sparks and explosions on every hit
- **Pause / Resume** — pause mid-game without losing state
- **No build step** — single self-contained HTML file

---

## 🔥 Power-Ups

| Icon | Name | Effect |
|------|------|--------|
| ⚡ | Speed | Increases movement speed for 5 seconds |
| 🛡 | Shield | Blocks the next hit (consumed on use) |
| 🔥 | Rapid | Triples fire rate for 4 seconds |
| 💥 | Triple | Fires 3-way spread shots for 5 seconds |
| ❤ | Heal | Restores 30 HP instantly |
| ☢ | Nuke | Deals 40 damage to opponent immediately |

---

## 🎮 Default Controls

| Action | Player 1 | Player 2 |
|--------|----------|----------|
| Move Up | `W` | `↑` |
| Move Down | `S` | `↓` |
| Move Left | `A` | `←` |
| Move Right | `D` | `→` |
| Fire | `Space` | `Enter` |
| Pause | `P` | `P` |

All controls can be rebound in the settings panel below the HUD.

---

## 🕹️ How to Play

1. Open `index.html` in any modern browser
2. Optionally remap controls and pick tank colors in the settings panel
3. Move around the arena, avoid bullets, collect power-ups
4. Reduce the opponent's HP to zero to win
5. Click **Play Again** to restart

---

## 📁 File Structure

```
tank-battle/
└── index.html    # Entire game — HTML, CSS, and JS in one file
```

---

## 🌐 Browser Compatibility

Works in any modern browser that supports the Canvas API and CSS `roundRect`. Tested in Chrome, Firefox, and Edge.

---

## 📝 License

MIT — see [LICENSE](LICENSE) for details.
