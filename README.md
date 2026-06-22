# FORJA ⚒️🔥

A fast-paced survival arcade roguelite running directly in your browser. The slag is coming for you, and your only defense is to shoot molten steel while managing your furnace's heat level. 



## 🎮 How to Play
Survive as long as possible, gather XP to unlock upgrades, and build a screen-clearing arsenal. The pace is frantic, and your thermal management dictates your combat capabilities.

**Controls:**
*   **WASD / Arrows:** Move
*   **Mouse:** Aim
*   **Click (Hold):** Shoot steel
*   **Space:** Dash (when unlocked)
*   **Keys 1, 2, 3:** Select upgrade cards
*   **Mobile:** Full touch support (drag to move/shoot)

## ⚙️ Technical Highlights
This project was built with a focus on optimization and pure system logic, packed into a single file:

*   **Zero Frameworks:** Built entirely with HTML5, CSS3, and Vanilla JavaScript.
*   **Custom Rendering:** Heavy use of the `<canvas>` API for particles, shadows, dynamic radial gradients, and a custom collision system.
*   **Procedural Audio:** All sound effects (shots, explosions, level up) are synthesized in real-time using the Web Audio API (Oscillators, BiquadFilters, and Gains) — no external MP3/WAV files.
*   **Smooth Game Loop:** Based on `requestAnimationFrame` with delta time (`dt`) calculations for consistent movement regardless of monitor refresh rates.


