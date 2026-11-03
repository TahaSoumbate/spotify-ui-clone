# 🎧 Spotify UI Clone — Flexbox vs CSS Grid

A recreation of the Spotify web-player home screen, built **twice** with pure HTML & CSS:
once with **Flexbox** and once with **CSS Grid** — so the two layout systems can be compared side by side.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![No Frameworks](https://img.shields.io/badge/frameworks-none-1ed760?style=flat)

---

## 🔗 Live demos

| Version | Link |
| --- | --- |
| 🏠 Landing | `https://TahaSoumbate.github.io/spotify-ui-clone/` |
| 1️⃣ Flexbox | `https://TahaSoumbate.github.io/spotify-ui-clone/flex/` |
| 2️⃣ Grid | `https://TahaSoumbate.github.io/spotify-ui-clone/grid/` |

---

## ✨ Features

- Header with navigation arrows, "Explore Premium" pill, and icon buttons
- Filter pills (All / Music / Podcasts)
- Artist shortcut grid (8 items)
- "Made For Forkani" section
- Daily Mix cards with hover lift
- Fully **responsive** (desktop → tablet → mobile)
- Smooth hover transitions everywhere
- Pure HTML + CSS, **zero dependencies**

---

## 🥊 Flexbox vs Grid

| Feature | Flex version | Grid version |
| --- | --- | --- |
| Layout model | 1-dimensional | 2-dimensional |
| Top bar | `display: flex` + `justify-content` | `display: grid` + `grid-template-columns` |
| Artist shortcuts | `flex-wrap` + `flex: 1 1 25%` | `grid-template-columns: repeat(4, 1fr)` |
| Daily mixes | `flex: 1 1 20%` | `repeat(5, minmax(0, 1fr))` |
| Best for | Linear content, wrapping | Precise 2-axis layouts |

---

## 📁 Project structure

```
spotify-ui-clone/
├── index.html           # landing page
├── public/
│   ├── css/             # landing.css, flex.css, grid.css
│   └── image/           # images
├── flex/index.html      # Flexbox version
└── grid/index.html      # CSS Grid version
```

---

## 🚀 Run locally

No build step needed — just open `index.html` in your browser, or use **Live Server** in VS Code.

---

## 🧠 What I learned

- Flexbox shines for **1D** distribution (nav bars, wrapping rows).
- Grid is cleaner when you know **exact column counts** (the shortcut and Daily Mix sections).
- Small details — hover states, `object-fit`, and media queries — do most of the "polish".

---

## 📄 License

MIT