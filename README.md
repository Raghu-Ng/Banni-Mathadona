# Banni Mathadona — The Podcast 🎙️

> *ಬನ್ನಿ ಮಾತಾಡೋಣ — Let's Talk*

A beautifully designed, static podcast website for **Banni Mathadona** — a Kannada-English podcast about building your home: the structure, the process, the money, and the people who make it all happen.

Hosted by **Anisha Katarki**, Founder of [StileDiVita](https://stiledivita.in).

---

## 📸 Preview

The site features a luxury editorial aesthetic with a warm cream-and-terracotta palette, editorial typography, and smooth micro-animations.

---

## 🗂️ Project Structure

```
Podcast/
├── index.html          # Main landing page (episode listing + about)
├── episodes/
│   ├── episode-1.html  # Full episode page — Ep 01
│   ├── episode-2.html  # Full episode page — Ep 02
│   └── episode-3.html  # Full episode page — Ep 03
└── README.md
```

---

## ✨ Features

- **Hero section** with animated fade-in and decorative SVG geometry
- **About the Podcast** strip with key stats
- **Host profile** section with quote
- **Episode grid** with live / coming-soon badges and hover effects
- **Individual episode pages** with full show notes, guest details, and embedded audio
- **Fully responsive** — mobile-first layout that works on all screen sizes
- **Zero dependencies** — pure HTML + CSS + vanilla JS, no frameworks or build tools required

---

## 🎨 Design System

| Token | Value | Usage |
|-------|-------|-------|
| `--cream` | `#f5f0e8` | Page background |
| `--ink` | `#1a1612` | Primary text |
| `--accent` | `#c4622d` | Terracotta highlight |
| `--ink-muted` | `#7a7168` | Secondary text |

**Fonts:** Cormorant Garamond (headings) · DM Sans (body) via Google Fonts

---

## 🚀 Getting Started

This is a **static website** — no build step or server required.

### Run locally

Simply open `index.html` in your browser:

```bash
# Option 1 — Open directly
start index.html

# Option 2 — Use a local dev server (e.g. VS Code Live Server extension)
# Right-click index.html → "Open with Live Server"

# Option 3 — Python simple server
python -m http.server 8080
# then visit http://localhost:8080
```

### Deploy to GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **`main` branch / `/ (root)`**
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

---

## 📻 Episodes

| # | Title | Status |
|---|-------|--------|
| 01 | *Laying the Foundation* | ✅ Live |
| 02 | *Coming soon* | 🔜 Upcoming |
| 03 | *Coming soon* | 🔜 Upcoming |

---

## 🛠️ Built With

- **HTML5** — semantic markup
- **Vanilla CSS** — custom design tokens, CSS Grid, Flexbox, animations
- **Vanilla JavaScript** — scroll interaction, audio player logic

---

## 📄 License

© 2025 StileDiVita / Anisha Katarki. All rights reserved.

---

*Made with ❤️ for Bangalore homebuilders.*
