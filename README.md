# linkvault# 🔗 LinkVault

> Save Once, Find Always — A minimal, fast personal link manager that runs entirely in your browser.

![LinkVault Preview](https://img.shields.io/badge/Status-Live-brightgreen) ![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-blue) ![Storage](https://img.shields.io/badge/Storage-Local-orange)

## ✨ Why I built this

I kept finding interesting websites on social media and saving them everywhere — browser bookmarks, phone notes, random tabs. I'd end up saving the same link 2–3 times without realising it, and could never find anything later.

LinkVault solves exactly that: one place for all your links, with instant duplicate detection and search.

## 🚀 Features

- **Duplicate Detection** — Automatically checks if you've already saved a URL the moment you paste it in. Never save the same link twice.
- **Auto Favicon** — Grabs the site icon so you can recognise links at a glance.
- **Tags** — Organise links with tags (e.g. `design`, `tools`, `学习`). Click a tag to filter.
- **Search** — Instantly search across title, URL, tags, and notes.
- **Notes** — Add a short note like "found on Twitter" or "check this later".
- **Zero backend** — Everything is stored in `localStorage`. No account, no server, no data leaving your device.
- **One file** — The entire app is a single `index.html`. Open it anywhere.

## 🛠️ Tech Stack

| Layer | Tech |
|-------|------|
| UI | Vanilla HTML + CSS |
| Logic | Vanilla JavaScript |
| Storage | Browser `localStorage` |
| Fonts | Google Fonts (Syne + DM Mono) |
| Favicons | Google S2 Favicon API |

No frameworks. No npm. No build step.

## 📦 Getting Started

### Option 1 — Just open the file
Download `index.html` and open it in your browser. Done.

### Option 2 — Host on GitHub Pages

```bash
git clone https://github.com/YOUR_USERNAME/linkvault.git
cd linkvault
# Enable GitHub Pages in repo Settings → Pages → Deploy from main branch
```

Your app will be live at `https://YOUR_USERNAME.github.io/linkvault`

## 💡 How to Use

1. Paste a URL into the input field
2. LinkVault immediately warns you if you've already saved it
3. Optionally add a title, note, and tags (press `Enter` after each tag)
4. Hit **Save Link**
5. Search or filter by tag anytime

## 🗺️ Roadmap

- [ ] Export/import as JSON or CSV
- [ ] Browser extension for one-click saving
- [ ] Cloud sync (optional, privacy-first)
- [ ] Click tracking to surface most-visited links

## 📄 License

MIT — do whatever you want with it.

---

*Built in one day during semester break. Scratching my own itch.*