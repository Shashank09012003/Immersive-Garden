# 🌿 Immersive Garden

> **Interactive WebGL Landing** — a small, immersive landing page showcasing custom GLSL shaders and modern frontend tooling.

[![Vite](https://img.shields.io/badge/bundler-vite-blue)]() [![JS](https://img.shields.io/badge/language-JavaScript-yellow)]() [![GLSL](https://img.shields.io/badge/GLSL-shaders-brightgreen)]()

---

## ✨ Demo
Open the project locally with `npm run dev` and visit `http://localhost:5173/` (Vite dev server).  
 The favicon is `src/assets/fav icon.png`.

---

## 🔍 What this is
An animated landing page (Immersive Garden) built with modern tooling and custom vertex/fragment GLSL shaders. Designed to demonstrate interactive visuals, lightweight performance, and shader-driven motion.

---

## 🚀 Features
- Custom **GLSL vertex & fragment shaders** for organic visuals.
- JavaScript module structure (`main.js`, `TrailTexture.js`) for modular effects.
- Vite + npm workflow for fast dev/refresh.
- Responsive HTML/CSS landing scaffold and SVG logo.
- Easy to extend with new shaders, audio-reactive elements, or UI overlays.

---

## 🧰 Tech stack
- HTML5, CSS3
- JavaScript (ES modules)
- GLSL (vertex + fragment shaders)
- Vite (dev server + bundler)
- npm (package management)
- (Optional) WebGL / lightweight renderer for shader usage

---

## 🗂 Project structure


├─ node_modules/
├─ public/
├─ src/
│ ├─ assets/
│ │ └─ fav icon.png
│ ├─ shaders/
│ │ ├─ fragment.glsl
│ │ └─ vertex.glsl
│ ├─ main.js
│ ├─ TrailTexture.js
│ └─ styles.css
├─ index.html
├─ package.json
└─ vite.config.js   


---

## 💻 Quick start (local)
1. Clone the repo  
```
git clone <your-repo-url>
cd immersive-garden 
```

2. Install
```
  npm install
```
3.Run dev server
```
npm run dev
```
4.Open browser: http://localhost:5173/

🧭 How it works (high-level)

index.html hosts the canvas + page layout and loads main.js.

main.js initializes the WebGL / renderer context and loads shaders from src/shaders/.

fragment.glsl + vertex.glsl drive pixel and vertex effects (colors, flow, noise).

TrailTexture.js contains reusable logic for trail or texture-based effects (particle trails, feedback, etc.).

Styling and layout handled via styles.css, SVG logo is embedded in the HTML header.   

✍️ Extend ideas

Add mouse or scroll interactivity to influence shader uniforms.

Add a simple GUI (dat.GUI / lil-gui) for live parameter tweaking.

Add lazy asset loading & fallback for mobile performance.

Export small GIF/WebM demo for social sharing.


📬 Contact   

Shashank Sharma  




