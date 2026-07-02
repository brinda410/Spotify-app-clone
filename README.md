# Spotify App Clone

A responsive, **pixel-accurate clone of the Spotify web player interface**, built with vanilla HTML5 and CSS3. Recreates the full app shell — sidebar, library, content grid, and a fully interactive-looking music player bar — with no frameworks involved.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![No JavaScript](https://img.shields.io/badge/JavaScript-None-lightgrey?style=flat)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## 🔴 Live Demo

> 🌐 [View Live Site](https://brinda410.github.io/Spotify-app-clone)

---

## ✨ Features

- 🎨 **Pixel-accurate layout** — sidebar, library panel, and content grid modeled directly on Spotify's real UI
- 🎵 **Full music player bar** — track info, playback controls, progress bar, and volume slider
- 📌 **Sticky content header** — scroll-aware nav with Premium/Install App call-to-actions
- 🧱 **Responsive card grid** — Recently Played, Trending, and Featured Charts sections using Flexbox wrap
- 🖱️ **Hover interactions** — nav items, icons, and progress/volume bars respond with opacity and accent-color transitions
- 📱 **Responsive breakpoints** — secondary UI elements progressively hide on smaller screens
- 🔤 **Google Fonts** — Montserrat & Poppins for clean, modern typography
- ⚡ **Zero JavaScript** — layout and interactivity styling done entirely in CSS

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic structure and component markup |
| CSS3 | Flexbox layout, transitions, fixed/sticky positioning |
| [Font Awesome 7](https://fontawesome.com/) | Navigation, player, and icon set |
| [Google Fonts – Montserrat & Poppins](https://fonts.google.com/) | Typography |

---

```
spotify-app-clone/
├── index.html
├── style.css
├── assets/
│   ├── logo.png
│   ├── library_icon.png
│   ├── backward_icon.png
│   ├── forward_icon.png
│   └── card1img.jpeg
├── LICENSE
└── README.md
```
---

---

## 🧠 Implementation Notes

- **Layout system**: A top-level flex container (`.main`) splits the sidebar and main content, with the player bar fixed independently at the bottom of the viewport.
- **Component-scoped naming**: Player sub-elements use an `mp-` prefix (`mp-track`, `mp-controls`, `mp-extra`) to avoid class collisions as the UI grows.
- **Responsive strategy**: Non-critical controls hide via a shared `.hide` utility class at the 1000px breakpoint.

---

## 📄 License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 👤 Author

**Brindashree R**
GitHub: @brinda410

⭐ If you found this useful, consider giving it a star!

> Built as a personal front-end project for learning and portfolio purposes. Not affiliated with or endorsed by Spotify.


