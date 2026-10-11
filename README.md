# Particle Sphere · Hand & Gesture Controlled

An interactive 3D WebGL particle sphere featuring real-time AI hand and gesture tracking via MediaPipe, dynamic multi-touch/mouse fallback controls, interactive color themes, pinch-to-charge explosions, and fluid particle animations.

![Particle Sphere Preview](https://img.shields.io/badge/WebGL-Interactive-blueviolet?style=for-the-badge)
![MediaPipe Hands](https://img.shields.io/badge/MediaPipe-Hands_Tracking-brightgreen?style=for-the-badge)
![Vanilla JS](https://img.shields.io/badge/Vanilla-JS_%26_CSS-orange?style=for-the-badge)
[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-22c55e?style=for-the-badge&logo=github)](https://sudeep06250.github.io/particle-sphere/)


---

## ✨ Features

- **3000 Fibonacci WebGL Particles**: High-performance mathematical distribution with depth-attenuated glowing points and additive blending.
- **Real-Time Hand & Gesture Control**:
  - ☝️ **Move & Rotate**: Move your hand across the webcam frame to translate and rotate the sphere in 3D space.
  - 🤏 **Pinch to Charge**: Pinch your thumb and index finger together to build up charge in the circular HUD meter, then release (or reach 100%) to detonate an explosion!
  - 🤚 **Fingers Palette Selector (0–5)**: Raise 0 to 5 fingers to instantly morph between 6 vibrant color palettes (Cosmic Violet, Electric Cyan, Neon Mint, Radiant Amber, Solar Coral, Astral Orchid).
  - 🙌 **Two-Hand Scale**: Bring two hands into view and spread or pinch them to dynamically resize the sphere diameter.
- **Seamless Mouse & Keyboard Fallback**:
  - Full experience remains 100% interactive even without a webcam or when camera permissions are disabled.
  - **Click & Drag**: Rotate and pan the sphere.
  - **Hold Click**: Charge the explosion ring and detonate.
  - **Scroll Wheel**: Smoothly zoom and scale the sphere.
  - **Number Keys (0–5) / Palette Pips**: Click on-screen pips or press `0`–`5` to change color themes.
  - **Spacebar**: Trigger an explosion.
- **Optimized & Self-Contained**: Pure vanilla JavaScript, CSS, and WebGL with zero build steps or heavyweight dependencies.

---

## 🚀 Quick Start

### 1. Run Locally
Because MediaPipe requires webcam access via a secure context (`http://localhost` or `https://`), launch a local web server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js npx
npx serve .
```

Open `http://localhost:8000` in Google Chrome, Microsoft Edge, or Firefox.

### 2. GitHub Pages
This project includes `index.html` at the repository root. You can enable **GitHub Pages** under **Settings > Pages > Deploy from branch (main / root)** for instant free hosting with HTTPS and full webcam support.

---

## 🛠️ Controls Summary

| Gesture / Input | Action |
| --- | --- |
| **Move Hand / Mouse Drag** | Rotate and steer the particle sphere |
| **Pinch Hand / Hold Left Click** | Charge up power meter and detonate particles |
| **Two Hands Spread / Mouse Scroll** | Dynamically scale sphere radius |
| **0 to 5 Fingers / Keys 0–5 / Click Pips** | Switch between 6 curated color palettes |
| **Spacebar** | Instantly trigger particle burst |
| **Webcam Toggle** | Switch webcam view between full and dimmed HUD |

---

## 📜 License
MIT License. Feel free to use, modify, and build upon this project!
