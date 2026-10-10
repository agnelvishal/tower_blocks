# Tower Blocks

A 3D isometric block-stacking arcade game built with Three.js and GSAP. Test your timing and reflexes by placing swinging blocks as precisely as possible to build the highest tower.

🔗 **Live Demo:** [https://agnelvishal.github.io/tower_blocks/](https://agnelvishal.github.io/tower_blocks/)

> **Note:** Created using **Claude** and **WhisprFlow** on an **Android phone**.

---

## 🎮 Gameplay & Features

- **Isometric 3D Graphics**: Rendered with Three.js WebGL orthographic projection and dynamic lighting.
- **Dynamic Block Slicing**: Any overhang on a placed block gets chopped off and tumbles down with physics-based animations.
- **Combo System**: Stack blocks with high accuracy to trigger bonus points and visual rewards.
- **Smooth Animations**: Powered by GSAP (TweenMax).
- **Responsive Controls**: Play via mouse click, touch tap, or by pressing the Spacebar.

---

## 🕹️ How to Play

1. Click or tap **Start** to begin the game.
2. Watch the block slide back and forth across the tower.
3. **Click, tap, or press Spacebar** to place the block onto the stack.
4. Try to align each block as accurately as possible with the previous one. Overhanging edges will be cut off, making subsequent blocks smaller!
5. The game ends when a block completely misses the tower.

---

## 🛠️ Tech Stack

- **HTML5 & CSS3**
- **JavaScript (ES6+)**
- **[Three.js](https://threejs.org/)** (3D WebGL rendering & geometry)
- **[GSAP](https://greensock.com/gsap/) (TweenMax)** (Camera motion and animation tweens)

---

## 🚀 Getting Started

Simply open `index.html` in any modern web browser or serve it using a local static server:

```bash
# Using python
python3 -m http.server 8000

# Or using npx serve
npx serve .
```

Then visit `http://localhost:8000` (or the port specified) in your browser.
