# OLUDO v1

A modern, immersive 3D web adaptation of the classic board game Ludo. Built with HTML5, CSS3, and JavaScript, leveraging Three.js for high-fidelity 3D graphics and animations.

## 🎮 Play Online
[https://oludov1.pages.dev](https://oludov1.pages.dev)

## ✨ Features

### 🎨 Visuals & Immersion
- **High-Fidelity 3D Graphics:** Real-time rendering with dynamic lighting and shadows using Three.js.
- **Realistic 3D Dice:** CSS 3D transformed cube with dot patterns and physics-based rolling animations.
- **Dual View Modes:** Seamlessly toggle between:
  - **Cinematic 3D:** Free camera controls to rotate and zoom around the board.
  - **Tactical 2D:** Top-down orthographic view for a classic board game feel.
- **5 Immersive Themes:**
  - 🌑 **Dark Mode** (Default)
  - ☀️ **Light Mode**
  - 🌲 **Forest**
  - 🏜️ **Desert**
  - 🌊 **Ocean**
- **Responsive Design:** Fully optimized for both Desktop (Mouse) and Mobile (Touch) devices.
- **Particle Effects:** Confetti celebration effects on wins and special rolls.

### 🎲 Gameplay Mechanics
- **Classic Rules:** Authentic Ludo experience including:
  - **The Rule of Six:** Roll a 6 to leave the base or get a bonus roll.
  - **Captures:** Land on an opponent to send them back to base.
  - **Safe Zones:** Stars and Start squares protect tokens from capture.
- **Local Multiplayer:** Play with up to 4 players (Red, Green, Yellow, Blue) on a single device.
- **Difficulty Modes:**
  - **Easy:** Highlights valid moves and active tokens with a visual ring.
  - **Hard:** No visual aids—classic board game challenge.
- **Game Timer:** Tracks the duration of your session.

### ⚙️ System & Settings
- **Save & Load System:**
  - 3 Local Save Slots.
  - Auto-save on exit or reset.
  - **Import/Export:** Transfer your game progress between devices using JSON files.
- **Audio Engine:**
  - Custom synthesized sound effects (Web Audio API) for rolling, stepping, capturing, and winning.
  - Background music/jingles.
  - Volume controls (High/Low) and Mute toggle.
- **Interactive Camera:**
  - **Rotate:** Drag to spin the board.
  - **Zoom:** Scroll or Pinch to zoom in/out.

### 🛠️ Technical Stack
- **Core:** Pure HTML5, CSS3, JavaScript (ES6+).
- **3D Engine:** Three.js (r128).
- **Animation:** Tweening for smooth token movement.
- **Styling:** CSS Variables for theming and responsiveness.
- **Storage:** LocalStorage for settings and game states.

## 🚀 How to Run
1.  Clone the repository or download the source code.
2.  Open `ludo.html` in any modern web browser.
3.  No build step or server required!

## 📜 License
Apache 2.0 License

---
*Created by GanjaSpider*
