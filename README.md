# 🧊 VanillaJS3D

A minimalist 3D engine built with **vanilla JavaScript** and **SVG**, entirely contained in a single `index.html` file. No WebGL, no libraries—just math, SVGs, and fun.

![screenshot](https://raw.githubusercontent.com/BadFoxAI/VanillaJS3D/main/screenshot.png) <!-- Add screenshot.png to the repo for this to work -->

## ✨ Features

- Perspective camera with orbit controls
- SVG-based real-time rendering (no canvas/WebGL)
- Interactive UI for wireframe toggle, zoom, and sphere segments
- Built-in support for cube and sphere primitives

## 🚀 Getting Started

1. Clone the repo  
2. Open `index.html` in your browser

```bash
git clone https://github.com/BadFoxAI/VanillaJS3D.git
cd VanillaJS3D
open index.html  # or double-click it
```

## 🎮 Controls

- **Mouse drag** – Rotate the camera
- **Scroll wheel** – Zoom in/out
- **UI sliders** – Adjust zoom and sphere detail
- **Wireframe toggle** – Switch rendering mode

## 🧠 How It Works

- 3D vector math using a custom `Vec3` class
- Orbit-style camera with projection math
- Faces sorted and shaded using painter's algorithm
- All rendering done via SVG `<polygon>` elements

## 📁 File Structure

```
VanillaJS3D/
├── index.html      # Core engine and UI (all-in-one)
└── LICENSE         # MIT License
```

## 📃 License

[MIT](https://github.com/BadFoxAI/VanillaJS3D/blob/main/LICENSE) – free to use, learn from, and build on.

---

⭐ Star this project if you find it useful or inspiring!
