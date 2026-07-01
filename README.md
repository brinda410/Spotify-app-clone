# Spotify App Clone

A high-fidelity, responsive clone of the Spotify web player interface, built with vanilla HTML5 and CSS3. Focused on pixel-accurate layout, realistic component structure, and scalable CSS architecture — no frameworks, no shortcuts.

> Built as a personal front-end project for learning and portfolio purposes. Not affiliated with or endorsed by Spotify.

### [Live Demo →](https://brinda410.github.io/spotify-app-clone/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Preview

![Spotify App Clone Preview](assets/preview.png)

## Features

- Persistent sidebar with Home/Search navigation and a Library panel including onboarding prompts (create playlist, browse podcasts)
- Sticky content header that remains fixed above scrollable content, with Premium/Install App call-to-actions
- Responsive card grid for Recently Played, Trending, and Featured Charts sections
- Full-featured music player bar, including:
  - Track artwork, title, and artist metadata
  - Playback controls (shuffle, skip, play/pause) with an emphasized primary play button
  - Interactive progress bar with hover-state accent color
  - Secondary controls (lyrics, queue, device connect) and a volume slider
- Responsive breakpoints that progressively hide non-essential UI on smaller viewports
- Consistent design system — shared spacing, radius, and opacity values across all components

## Tech Stack

| Category | Tools |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (Flexbox) |
| Icons | Font Awesome 7 |
| Typography | Google Fonts — Montserrat, Poppins |

## Project Structure
spotify-app-clone/
├── index.html          # Main markup — sidebar, content, player
├── style.css            # All component and layout styling
├── assets/
│   ├── preview.png
│   ├── logo.png
│   ├── library_icon.png
│   ├── backward_icon.png
│   ├── forward_icon.png
│   └── card1img.jpeg ... card6img.jpeg
├── LICENSE
└── README.md
## Getting Started

**View live:** [spotify-app-clone](https://brinda410.github.io/spotify-app-clone/)

**Run locally:**

No build step or dependencies required — open directly, or use Live Server for hot-reload during development.

```bash
git clone https://github.com/brinda410/spotify-app-clone.git
cd spotify-app-clone

# Option 1: open directly
open index.html

# Option 2: with hot-reload (recommended for editing)
npx live-server
```

## Implementation Notes

- **Layout system**: A top-level flex container (`.main`) splits the sidebar and main content, with the player bar fixed independently at the bottom of the viewport.
- **Component-scoped naming**: Player sub-elements use an `mp-` prefix (`mp-track`, `mp-controls`, `mp-extra`) to avoid class collisions and keep styles predictable as the UI grows.
- **Responsive strategy**: Non-critical controls (volume label, artist name, secondary player icons) are hidden via a shared `.hide` utility class at the 1000px breakpoint, keeping the responsive approach lightweight and low-complexity.
- **Interaction feedback**: Interactive elements use opacity and color transitions on hover rather than layout shifts, for smooth, consistent UI feedback.

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

## Author

Brindashree R
