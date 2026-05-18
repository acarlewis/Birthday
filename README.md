# 🎂 Happy Birthday — Akana Carlewis

A personalised interactive birthday webpage featuring animated fireworks, synthesised sound effects, and optional background music. Built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies.

---

## ✨ Features

- **Interactive fireworks** — click or tap anywhere on the screen to launch fireworks at that exact spot
- **Auto-launching fireworks** — fireworks fire automatically so the page is always alive
- **Synthesised sound effects** — launch whistle and explosion sounds generated in real time via the Web Audio API (no audio files required for SFX)
- **Background music** — drop a `birthday.mp3` in the project folder and it plays automatically on first interaction
- **Fully responsive** — works on desktop and mobile; touch events supported
- **Zero dependencies** — single HTML file, no npm, no build step

---

## 🚀 Live Demo

> 🔗 `https://acarlewis.github.io/YOUR_REPO/`
> *(update this after deploying to GitHub Pages)*

---

## 📁 Project Structure

```
├── index.html        # Everything — markup, styles, and script in one file
└── birthday.mp3      # Optional — add your own MP3 for background music
```

---

## 🎵 Adding Background Music

1. Find an MP3 you'd like to use (e.g. a birthday song)
2. Rename it to `birthday.mp3`
3. Place it in the same folder as `index.html`
4. Music will autoplay (muted until the user first clicks, due to browser policy)

If no `birthday.mp3` is present, everything still works — only the background music is missing.

---

## 🌍 Hosting on GitHub Pages

1. Create a new **public** repository on [github.com](https://github.com)
2. Push your files:
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```
3. Go to **Settings → Pages**
4. Set source to **Deploy from a branch → main → / (root)**
5. Your site goes live at `https://YOUR_USERNAME.github.io/YOUR_REPO/`

---

## 🛠️ Customisation

All personalisation is in `index.html`:

| What | Where |
|---|---|
| Main heading | `<h1>Happy Birthday</h1>` |
| Person's name | `<h2>AKANA CARLEWIS</h2>` |
| Credits text | `<p class="credits">...</p>` |
| Background colour | `background: #020202` in CSS |
| Firework colours | `shade` range in `onClick()` and `update()` |
| Firework count on click | `random(3, 5)` in `onClick()` |

---

## 🧰 Built With

- Vanilla HTML, CSS & JavaScript
- [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) — for synthesised sound effects
- [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) — for firework animations
- [Google Fonts — Source Sans 3](https://fonts.google.com/specimen/Source+Sans+3)

---

*Developed by carlewis 🎉*
