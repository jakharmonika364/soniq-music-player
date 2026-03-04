![Status](https://img.shields.io/badge/🚀%20Status-MVP%20in%20Development-7C5CFF?style=for-the-badge)

# 🎧 SONIQ – Music Streaming Platform

SONIQ is a modern, Spotify-inspired music streaming platform with **Remix** and **Karaoke** features, built using **HTML, CSS, and JavaScript**, focusing on smooth UX, performance, and creator-friendly experiences.

---

🎨 Design: Figma (https://www.figma.com/make/EYhs7ocUxBkLu7tqiUHYYg/Music-Streaming-Platform-Design?t=yY7M509Yw8K8c4kG-1)


## ✨ Expected Features

- 🎵 Music streaming with waveform visualization
- 🔍 Search & playlist management
- 🎬 Remix mode – create short reel-style videos using music
- 🎤 Karaoke mode – sing with synced lyrics
- 🔐 Authentication using Supabase
- 🌊 Animated backgrounds & micro-interactions
- ⚡ Lightweight, client-first architecture

---

## 🧠 Tech Stack

**Frontend**
- HTML5
- CSS3 (Animations & Effects)
- JavaScript (Vanilla)

**Media & APIs**
- Web Audio API
- MediaRecorder API
- Canvas / CSS Filters

**Backend / Services**
- Supabase (Auth + Database)
- External Music APIs (no local song storage)

**Deployment**
- Vercel / Netlify (Planned)

---

## 📂 Project Structure

```text
soniq-music-player/
│
├── public/
│ └── index.html
│
├── src/
│ ├── styles/
│ │ ├── base.css
│ │ ├── player.css
│ │ ├── remix.css
│ │ ├── karaoke.css
│ │ └── animations.css
│ │
│ ├── scripts/
│ │ ├── app.js # entry point
│ │ ├── state.js # global app state
│ │ ├── auth.js # supabase auth
│ │ ├── audio.js # player logic
│ │ ├── waveform.js
│ │ ├── remix.js
│ │ ├── karaoke.js
│ │ └── api.js # song fetching
│ │
│ ├── components/
│ │ ├── player.js
│ │ ├── playlist.js
│ │ ├── modal.js
│ │
│ └── utils/
│ ├── helpers.js
│ └── constants.js
│
├── assets/
│ ├── images/
│ └── icons/
│
├── docs/
│ ├── architecture.md
│ ├── api-notes.md
│ └── decisions.md
│
├── .gitignore
├── LICENSE
└── README.md
