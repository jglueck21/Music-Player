# 🎵 Music Player

A simple **web-based music player** that lets users upload songs, play them, and manage playback — all stored locally using the **IndexedDB API**.

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Audio:** Web Audio API
- **Storage:** IndexedDB (for offline persistence)

---

## ✨ Features

### ✅ Core Functionality (MVP)

- Upload and play audio files from your device  
- Playback controls: Play / Pause / Skip / Loop / Volume  
- Automatically saves last played song (IndexedDB)

### ✅ Advanced Features

- Visualizer using Web Audio API  
- Mobile responsive layout  
- Dark mode  
- Offline-capable via IndexedDB

---

## 📁 Project Structure

```
Music-player/
├── Assets/
│   ├── indexedDB.js
│   ├── Themes.css
│   ├── Themes.js
│   └── Songs.mp3
│
├── Library/
│   ├── assets/
│   ├── Playlist/
│   │   ├── Playlist.html
│   │   ├── style.css
│   │   └── script.js
│   ├── Library.html
│   ├── Style.css
│   └── script.js
│
├── Player/
│   ├── Player/
│   │   ├── Player.html
│   │   ├── style.css
│   │   └── script.js
│   └── Player-vinyl/
│       ├── Player-vinyl.html
│       ├── style.css
│       └── script.js
│
├── Settings/
│   ├── Player/
│   │   ├── Player-settings.html
│   │   ├── Style.css
│   │   └── script.js
│   ├── Themes/
│   │   ├── Themes.html
│   │   ├── style.css
│   │   └── Script.js
│   ├── Settings.html
│   ├── style.css
│   └── script.js
│
├── index.html
├── style.css
└── script.js
```


---

> ✅ No frameworks. This project is built with clean, vanilla HTML/CSS/JS for better control and understanding.

---

## 🧭 Development Phases

### Phase 1 – Core UI and Functionality

- ✅ Built basic layout with HTML and CSS  
- ✅ Set up audio controls with JavaScript  
- ✅ Integrated IndexedDB to persist song info

### Phase 2 – Enhancements

- ✅ Added song visualizer using Web Audio API  
- ✅ Implemented drag-and-drop UI for uploads  
- ✅ Created mobile-first responsive layout  
- ✅ Introduced Dark Mode toggle

---

## 👨‍💻 Team Setup (for potential collaboration)

Currently a **solo project**, but could be split as:

- 🎨 UI & Styling  
- 🎵 Audio Control & Playback Logic  
- 💾 Data Persistence (IndexedDB & State Logic)

---

## 🔗 Live Demo

_You can host this via GitHub Pages or Netlify_

---

## 📚 References

- [MDN: IndexedDB API](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)  
- [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)

---

## 📌 Status

🚧 Still under development.  
More features like playlists and metadata tagging are planned.
