# 🪐 CosmosExplorer — Interactive 3D Solar System

> **An immersive, browser-based 3D solar system built entirely in vanilla HTML, CSS & JavaScript using Three.js — no frameworks, no backend, no install required.**

**Made by [Arunava Ghosh](https://linkedin.com/in/) · India 🇮🇳**

---

## 🚀 Live Demo

> Open `[solar-system.html](https://arunavaghosh42428.github.io/cosmos-explorer-3d/)` directly in any modern browser — no server needed.
<a href="https://www.google.com">Go to Google</a>
---

## ✨ Features

### 🌍 Core Experience
- **Interactive 3D Solar System** — Click & drag to orbit, scroll/pinch to zoom, click any planet to focus
- **Procedural Planet Textures** — Every planet surface generated with fractal noise algorithms (no external images)
  - ☀️ Sun with plasma turbulence & corona glow layers
  - ☿ Mercury with impact craters
  - ♀️ Venus with swirling sulfuric cloud bands
  - 🌍 Earth with procedural continents, oceans, polar ice caps, and a separate rotating cloud layer
  - ♂️ Mars with iron-oxide surface, polar caps, and crater dimming
  - ♃ Jupiter with atmospheric bands + Great Red Spot storm
  - ♄ Saturn with banded atmosphere + multi-layered textured rings (Cassini Division included)
  - ⛢ Uranus with limb-darkened teal atmosphere
  - ♆ Neptune with dynamic storm bands + Dark Spot feature
- **Bump Maps** — Surface relief on Mercury, Earth, and Mars
- **Orbit Visualisations** — Toggle elliptical paths on/off
- **Planet Labels** — Projected 3D labels with emoji

### 📋 Planet Profiles
- Mass, diameter, distance, moon count
- Atmosphere composition
- Surface composition
- Known moons list
- Mythology & origin of name
- Fun fact per planet

### ⏱️ Time Travel
- Slider from year 1975 → 2075
- Preset buttons for quick jumps
- Planetary positions update in real-time

### 📡 Motion Sensor (Mobile)
- **Gyroscope mode** — Tilt your phone to orbit the solar system
- **iOS 13+ permission handling** — Clear Allow/Deny flow with recovery instructions
- **Keyboard fallback mode** — Arrow keys control the camera on any device
- Sensitivity slider, live calibration, bubble visualiser with Alpha/Beta/Gamma readout

### 🛠️ Other Tools
- 🔍 **Search & Filter** — Find any planet instantly
- ⚡ **Gravity Simulator** — Launch objects and watch them orbit or crash into the Sun
- 📏 **Size Comparison Tool** — Side-by-side scale comparison of any two bodies
- 🛸 **Space Mission Tracker** — Perseverance, JWST, Voyager 1, Parker Probe, Artemis, New Horizons
- 🚀 **Space Quiz** — 8 trivia questions with explanations
- 🌟 **Personality Test** — "Which planet are you?" — 5-question quiz
- 🔊 **Audio Tour** — Narrated tour via Web Speech API
- ♿ **Accessibility Panel** — High contrast, large text, reduced motion, text-to-speech

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| [Three.js r128](https://threejs.org) | 3D rendering, lighting, camera |
| Vanilla JavaScript | All logic, textures, UI |
| HTML5 Canvas API | Procedural texture generation |
| Web Speech API | Audio narration |
| DeviceOrientation API | Gyroscope / motion controls |
| Pure CSS | All UI, animations, panels |

> **Zero dependencies installed.** Three.js loaded from CDN. Everything else is hand-written.

---

## 📁 File Structure

```
cosmos-explorer-3d/
│
└── solar-system.html      # Entire app — single self-contained file (~72 KB)
```

Yes, the entire application — 3D engine, procedural textures, all features, all data — lives in **one HTML file**.

---

## 🖥️ How to Run

### Option 1 — Just open the file
```bash
# Download and double-click solar-system.html
# Works in Chrome, Firefox, Edge, Safari
```

### Option 2 — Serve locally (recommended for motion sensor on iOS)
```bash
# Python
python3 -m http.server 8080

# Node.js
npx serve .

# Then open: http://localhost:8080/solar-system.html
```

> ⚠️ **iOS Motion Sensor** requires HTTPS or localhost. Use a local server or deploy to GitHub Pages.

---

## 📱 Mobile Support

| Feature | iOS Safari | Android Chrome |
|---|---|---|
| 3D rendering | ✅ | ✅ |
| Touch drag & pinch-zoom | ✅ | ✅ |
| Gyroscope control | ✅ (permission required) | ✅ (auto) |
| Audio tour | ✅ | ✅ |
| All panels | ✅ | ✅ |

---

Your live URL: `https://arunavaghosh42428.github.io/cosmos-explorer-3d/`

---

## 📸 Screenshots

> 
<img width="1920" height="1118" alt="Screenshot 2026-03-04 at 2 52 07 PM" src="https://github.com/user-attachments/assets/80b75fb4-66b3-4cff-b12a-999bd7e8955d" />

---

## 🔭 Roadmap / Ideas

- [ ] Real NASA APOD / Horizons API integration
- [ ] Asteroid belt particle system
- [ ] Pluto & dwarf planets
- [ ] Comet trajectories
- [ ] VR mode (WebXR)
- [ ] Save/share custom time presets

---

## 👤 Author

**Arunava Ghosh** · India 🇮🇳

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

> *"The cosmos is within us. We are made of star-stuff." — Carl Sagan*
