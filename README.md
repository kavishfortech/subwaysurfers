# ⚡ NEON SURFER 3D 
### *Architect: Kavish Shah | Neural Interface v1.0*



## 🌐 Live Access
**Deployment Link:** [https://kavishfortech.github.io/Subwaysurfers](https://kavishfortech.github.io/Subwaysurfers)

---

## 🛠 Engineering Overview
This project is a custom-built **Pseudo-3D Infinite Runner**. Instead of using a heavy 3D engine like Three.js, it utilizes a lightweight **Perspective Projection Matrix** written in Vanilla JavaScript.

### The Math behind the Depth
To simulate 3D movement on a 2D canvas, every object exists on a Z-axis. As the object's $Z$ value decreases (approaches the viewer), its size and position are calculated using:

$$X_{screen} = CenterX + (X_{lane} \times \frac{Width}{Z})$$
$$Y_{screen} = HorizonY + (\frac{Height}{Z})$$
$$Size = \frac{BaseSize}{Z}$$

## 🚀 System Features
* **Vector Lane Logic:** 3-lane navigation system (-1, 0, 1) with smooth interpolation.
* **Vortex Floor Grid:** A dynamic scrolling grid that creates a sense of high-velocity movement.
* **Performance Monitoring:** Integrated 60 FPS real-time tracker and dynamic score scaler.
* **Neon UI:** Signature **Architect Theme** with color-shifting borders and scanline filters.

## 🕹 Controls
* **Mobile:** Integrated touch-pad buttons for lane switching.
* **Desktop:** `Left Arrow` and `Right Arrow` keys.
* **Goal:** Dodge the pink "Data Corruption" blocks to maintain system integrity.

---

## 🏗 Installation
1.  Clone this repository:
    ```bash
    git clone [https://github.com/kavishfortech/Subwaysurfers.git](https://github.com/kavishfortech/Subwaysurfers.git)
    ```
2.  Open `index.html` in any modern web browser.
3.  Ensure your browser supports **HTML5 Canvas** for optimal performance.

---
*Created by [Kavish Shah](https://kavishfortech.github.io/Kavishforgames) — Systems Architect.*
