# Asteroid_Destroyer

---

## ▶️ How to run

Open the `index.html` file in any modern browser (Chrome, Firefox, Edge, Safari):

1. Double-click `index.html` or serve the folder via a simple HTTP server.
   - Using Python (recommended for local testing):
     ```bash
     # Python 3
     python -m http.server 8000
     # Then open: http://localhost:8000
     ```
2. From the main menu, click **Gemini 2.5 Pro** or **Claude 3.7 Sonnet** to play.

---

## 🎮 Controls

- `Arrow keys` or `W A S D` — move / turn.
- `Space` or `Z` — shoot lasers.
- `H` — hyperspace jump (limited / cooldown).
- Game UI shows score, lives, laser cooldown and hyperspace status.

---

## ✨ Features & Mechanics

- **Starfield parallax** for depth and atmosphere.
- **Ship physics**: thrust, friction, max speed and smooth rotation for classic asteroids-style gameplay.
- **Asteroids & fragments**: bigger rocks break into fragments, increasing chaos.
- **Laser cooldown & UI**: visual bar shows firing readiness.
- **Hyperspace**: random teleport with a (small) chance of malfunction — use strategically.

---

## 🛠️ Customize

Want to tweak difficulty, visuals or controls? Open the HTML files and edit variables at the top of the `<script>`:

- `ASTEROID_SPAWN_RATE`, `ASTEROID_SPEED_MIN/MAX`, `LASER_COOLDOWN`, `INITIAL_LIVES`, etc. — tweak these to balance difficulty.

CSS variables in the files control colors and theme (useful for quick “reskinning”):

```css
:root {
  --game-bg: #0a0a1a;
  --ship-color: #00f0f0;
  --laser-color: #ff00ff;
  --ui-text-color: #00ff00;
}

⚖️ License & Credits

* You own the code in this project (unless you say otherwise).
* Add a license file if you want to open-source it (MIT is a good permissive choice).
* Built with vanilla HTML/CSS/JS. Fonts used: Press Start 2P (Google Fonts) in some variants.
"""
🗂 Project structure
/ (root)
├─ index.html        # Main menu / launcher (links to Gemini & Claude versions). :contentReference[oaicite:3]{index=3}
├─ gemini.html       # Gemini 2.5 Pro themed variant of the game. :contentReference[oaicite:4]{index=4}
├─ claude.html       # Claude 3.7 Sonnet themed variant of the game. :contentReference[oaicite:5]{index=5}
└─ README.md         # (this file)
Screenshot:
<img width="1905" height="806" alt="image" src="https://github.com/user-attachments/assets/fe5c6ef0-79a9-4a76-a673-464c7cea07fb" />

