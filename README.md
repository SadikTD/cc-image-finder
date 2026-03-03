# 📸 CC Image Finder

A browser-based tool that searches **6 free image sources simultaneously**, auto-resizes images, generates proper attribution, and downloads — all in one click. Built for content teams who need CC-licensed images fast.

🔗 **Live:** [sadiktd.github.io/cc-image-finder](https://sadiktd.github.io/cc-image-finder/)

---

## ✨ Features

### Core
- **6-source search** — Openverse, Wikimedia Commons, Flickr, Unsplash, Pixabay, and Pexels in one unified grid
- **Auto-resize** — Downloads are cropped and resized to your configured dimensions (default 1200×675)
- **Auto-attribution** — Proper credit text is generated and copied to clipboard on every download
- **Focal point cropping** — Click where the face or key area is before cropping so nothing important gets cut off
- **Search suggestions** — Wikipedia-powered autocomplete as you type

### 🔲 Overlay Combiner
Combine two images into one — a background image with a circular overlay portrait. Perfect for article thumbnails.

1. Download any image → set focal point → click **"Add Overlay"**
2. Choose the site: **WGTC** (orange ring) or **AOTF** (4-color ring)
3. Search for the overlay image inside the modal, pick it, set its focal point
4. Preview the combined result → download

Both credits are saved automatically.

### Organization
- **Credits Log** — Every download's attribution is tracked. Copy all or export as `.txt`
- **Favorites** — Star images to save for later. Persists across sessions
- **Search history** — Recent searches with one-click reuse
- **Bulk operations** — Select multiple images, download all or copy all credits at once
- **Download queue** — Visual progress for each download

### Customization
- **Custom filenames** — Template with variables: `{query}`, `{title}`, `{source}`, `{creator}`, `{date}`, `{timestamp}`
- **Grid sizes** — Small, Medium, or Large card layouts
- **Text scaling** — 5 sizes from Small to Extra Large
- **Dark / Light theme** — Toggle with one click
- **Sound effects** — Audio feedback on downloads

### Navigation
- **Keyboard shortcuts** — `Enter` search, `Ctrl+K` focus, arrows navigate, `D` download, `C` credit, `F` favorite, `Space` select, `Esc` close
- **Right-click menu** — Quick actions on any image card
- **Responsive design** — Works on desktop, tablet, and mobile

---

## 🚀 Getting Started

### For users
Just open the [live site](https://sadiktd.github.io/cc-image-finder/) and start searching. All API keys are pre-configured — it works out of the box.

### For admins
API keys are hidden by default. Press `Ctrl+Shift+A` to unlock the API Keys tab in Settings.

### Self-hosting
It's a single HTML file. Download `index.html` and open it in any browser, or host it on any static server.

---

## 📂 Sources

| Source | License Types | API Key | Rate Limit |
|--------|--------------|---------|------------|
| **Openverse** | CC BY, CC BY-SA, CC0, PDM | Required (free) | 10,000/day |
| **Wikimedia Commons** | CC BY, CC BY-SA, Public Domain | Not needed | Unlimited* |
| **Flickr** | CC BY, CC BY-SA, CC0, Public Domain | Required (free) | 3,600/hour |
| **Unsplash** | Unsplash License (free commercial use) | Required (free) | 50/hour (demo) |
| **Pixabay** | Pixabay License (free commercial use) | Required (free) | 6,000/hour |
| **Pexels** | Pexels License (free commercial use) | Required (free) | 200/hour |

*Wikimedia asks for respectful usage but has no hard rate limit.

---

## 📝 Attribution Formats

Each source generates its own standard credit:

- **Openverse:** `"Photo Title" by Creator, CC BY 4.0.`
- **Wikimedia:** `"Photo Title" by Creator, CC BY-SA 3.0. Via Wikimedia Commons.`
- **Flickr:** `"Photo Title" by Creator, CC BY 2.0.`
- **Unsplash:** `Photo by Creator on Unsplash.`
- **Pixabay:** `Image by Creator on Pixabay.`
- **Pexels:** `Photo by Creator on Pexels.`

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Enter` | Search / Open preview |
| `Ctrl+K` | Focus search bar |
| `← → ↑ ↓` | Navigate grid |
| `D` | Download selected image |
| `C` | Copy credit |
| `F` | Toggle favorite |
| `Space` | Toggle select |
| `Esc` | Close modals |
| `Ctrl+Shift+A` | Unlock API Keys tab |

---

## 🏗 Technical

- **Zero dependencies** — Single HTML file, no build step, no framework
- **Client-side only** — Runs entirely in the browser, no server needed
- **API keys in localStorage** — Never transmitted to any third party
- **CORS-safe** — All APIs support cross-origin requests
- **~82KB** — Entire app including CSS and JS

---

## 📄 License

Free to use and modify. Created by **Sadik Hossain**.
