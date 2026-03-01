# 📸 CC Image Finder

A powerful, browser-based tool to search and download Creative Commons licensed images from multiple sources — all in a single HTML file.

🔗 **Live Demo:** [Visit CC Image Finder](https://sadiktd.github.io/cc-image-finder/)

---

## ✨ Features

- **Multi-source search** — Search across Openverse, Flickr, Unsplash, Pixabay, and Pexels simultaneously
- **Auto-resize & crop** — Download images resized to your custom dimensions (default 1200×675)
- **Focal point picker** — Click on the face or key area before cropping so nothing important gets cut off
- **Auto credit copy** — Attribution text is copied to your clipboard on every download
- **Custom filenames** — Use template variables like `{query}`, `{source}`, `{creator}`, `{date}`
- **Dark & light themes** — Toggle between dark and light mode
- **Favorites** — Star images and access them anytime
- **Bulk operations** — Select multiple images and download or copy all credits at once
- **Keyboard navigation** — Arrow keys to browse, `D` to download, `C` for credit, `F` to favorite
- **Credits log** — Running list of all credits from your session, exportable as `.txt`
- **Download queue** — Visual progress bars for each download
- **Right-click context menu** — Quick actions on any image card
- **Search history** — Recent searches accessible from the search bar dropdown
- **Text size control** — Adjustable text size from Small to Extra Large
- **Pagination** — Load more results with no limit
- **Fully responsive** — Works on desktop, tablet, and mobile
- **No server needed** — Runs entirely in the browser as a single HTML file

## 🔑 API Keys Setup

All API keys are **free** and stored locally in your browser (never sent anywhere except to the respective APIs).

| Source | How to get a free key |
|---|---|
| **Openverse** | [Register here](https://api.openverse.org/v1/auth_tokens/register/) — you'll get a `client_id` and `client_secret` |
| **Flickr** | [Apply here](https://www.flickr.com/services/api/misc.api_keys.html) |
| **Unsplash** | [Sign up here](https://unsplash.com/developers) |
| **Pixabay** | [Get key here](https://pixabay.com/api/docs/) |
| **Pexels** | [Get key here](https://www.pexels.com/api/) |

Once you have your keys, click ⚙️ **Settings** → **API Keys** tab → paste them in → **Save**.

## 🚀 How to Use

1. Visit the live link above
2. Enter your API keys in Settings (one-time setup)
3. Type a search term and hit Enter
4. Browse results, preview, download, and copy credits

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| `Enter` | Search / Preview selected |
| `Ctrl+K` | Focus search bar |
| `← → ↑ ↓` | Navigate grid |
| `D` | Download selected image |
| `C` | Copy credit |
| `F` | Toggle favorite |
| `Space` | Select/deselect for bulk |
| `Esc` | Close any modal |

## 📄 License

MIT License — free to use, modify, and share.

---

**Created by Sadik Hossain**
