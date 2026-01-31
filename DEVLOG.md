# Portfolio Devlog — Tamer Altaweel

Tracking the build-out of my portfolio and all showcase projects.

---

## Roadmap

| # | Project | Type | Stack | Status |
|---|---------|------|-------|--------|
| 0 | Portfolio Website | Frontend | HTML, CSS, JS | Done |
| 1 | WeatherNow | Full Stack Web App | HTML, CSS, JS, Open-Meteo API | Done |
| 2 | QuickTask | Mobile / PWA | React, Firebase, PWA | Pending |
| 3 | DevVault | API / Backend | Node.js, Express, MongoDB, JWT Auth | Pending |
| 4 | ChatBot AI | AI Integration | React, Node.js, OpenAI API | Pending |
| 5 | PixelDraw | Creative / Fun | HTML Canvas, JS | Done |
| 6 | TypingArena | Game / Interactive | Vanilla JS, CSS Animations | Done |
| 7 | LinkForest | Utility / SaaS | React, Node.js, MongoDB, Short URLs | Pending |
| 8 | SoundBoard | Audio / Fun | Web Audio API, JS, CSS Grid | Done |
| 9 | OmniStream | Android App | Kotlin, Jetpack Compose, Hilt, Room | Done |

---

## Project Descriptions

### 1. WeatherNow — Weather Dashboard
A sleek weather app with location search, 5-day forecast, animated weather icons, and light/dark theme. Pulls live data from OpenWeather API. Shows full stack skills — API calls, server proxy to hide keys, responsive UI.

**Key features:**
- Search any city worldwide
- Current conditions + 5-day forecast
- Animated weather icons and backgrounds
- Geolocation support
- Server-side API proxy (hides API key)

**Repo:** `TamerAli-0/weather-now`

---

### 2. QuickTask — Task Manager PWA
A drag-and-drop task manager that works offline. Installable as a Progressive Web App. Shows mobile/app skills, local storage, service workers, and clean UI/UX.

**Key features:**
- Create, edit, delete tasks
- Drag-and-drop between columns (To Do / In Progress / Done)
- Offline support via Service Worker
- Installable PWA (add to home screen)
- Local storage persistence
- Filter and search

**Repo:** `TamerAli-0/quick-task`

---

### 3. DevVault — Secure Code Snippet API
A REST API for storing and retrieving code snippets with user auth. Full backend project with JWT authentication, CRUD operations, and API documentation. Shows backend mastery.

**Key features:**
- User registration and login (JWT)
- CRUD for code snippets (create, read, update, delete)
- Syntax language tagging
- Search and filter endpoints
- Rate limiting and input validation
- API docs page

**Repo:** `TamerAli-0/dev-vault`

---

### 4. ChatBot AI — AI Chat Interface
A ChatGPT-style conversational interface powered by OpenAI's API. Shows AI integration, streaming responses, conversation history, and polished frontend.

**Key features:**
- Real-time streaming responses
- Conversation history with local storage
- Markdown rendering in responses
- Code block syntax highlighting
- Mobile responsive chat UI
- Backend proxy for API key security

**Repo:** `TamerAli-0/chatbot-ai`

---

### 5. PixelDraw — Multiplayer Pixel Art Canvas
A collaborative pixel art drawing app where multiple users can draw on the same canvas in real time. Think r/place but your own version. Colorful, addictive, and shows off WebSocket skills.

**Key features:**
- Grid-based pixel canvas with color palette
- Real-time multiplayer drawing via WebSockets
- Undo/redo history
- Export canvas as PNG
- Gallery of saved artworks
- Zoom and pan controls

**Repo:** `TamerAli-0/pixel-draw`

---

### 6. TypingArena — Typing Speed Game
A competitive typing speed test with leaderboards, difficulty modes, and live WPM/accuracy tracking. Satisfying animations on every keystroke. People love typing games — guaranteed to impress.

**Key features:**
- Real-time WPM and accuracy tracking
- Multiple difficulty modes (easy, medium, hard, code mode)
- Keystroke sound effects and visual feedback
- Local + global leaderboard
- Race against the clock or endless mode
- Share results with screenshot

**Repo:** `TamerAli-0/typing-arena`

---

### 7. LinkForest — URL Shortener & Bio Links
A link shortener with analytics, plus a "link in bio" page builder (like Linktree). Practical, useful, and shows database + auth + dashboard skills.

**Key features:**
- Shorten any URL with custom aliases
- Click analytics (count, referrer, location)
- Personal bio link page builder
- Custom themes for bio page
- QR code generation
- User accounts with dashboard

**Repo:** `TamerAli-0/link-forest`

---

### 8. SoundBoard — Interactive Sound Pad
A drum machine / sound pad where users tap colorful pads to trigger sounds. Supports keyboard shortcuts, recording loops, and beat sequencing. Fun, visual, and instantly impressive in a demo.

**Key features:**
- 16-pad grid with keyboard mapping (A-Z keys)
- Multiple sound packs (drums, synth, FX, memes)
- Record and playback loops
- Beat sequencer with BPM control
- Visual ripple effects on pad hits
- Volume and pitch controls per pad

**Repo:** `TamerAli-0/sound-board`

---

## Log

### Day 1 — Jan 29, 2026
- [x] Created portfolio website (HTML/CSS/JS)
- [x] Added particle background, typewriter, scroll animations, glassmorphism
- [x] Set up GitHub account integration
- [x] Pushed portfolio to `TamerAli-0/portfolio`
- [x] Enabled GitHub Pages — live at https://tamerali-0.github.io/portfolio/
- [x] Added README
- [x] Created devlog and project roadmap
- [x] Built Project 1 — WeatherNow (weather dashboard with dynamic themes)
- [x] Pushed to `TamerAli-0/weather-now` + enabled GitHub Pages
- [x] Updated portfolio project cards with real repo links
- [x] Built TypingArena — typing speed game with WPM tracking, 4 difficulty modes, leaderboard
- [x] Built SoundBoard — drum machine with 4 sound packs, beat sequencer, beat generator (5 styles)
- [x] Built PixelDraw — pixel art canvas with tools, palette, undo/redo, PNG export, gallery
- [x] Pushed all 3 to GitHub + enabled GitHub Pages
- [x] Switched WeatherNow to Open-Meteo API — fully functional, no API key needed
- [x] Pushed OmniStream (Kotlin/Android) to `TamerAli-0/OmniStream`
- [x] Updated portfolio: OmniStream as flagship project, Kotlin/Java skills, expanded grid
- [x] Added beat generator to SoundBoard (Trap, Boom Bap, House, Drill, Lo-Fi)

### Day 2 — Jan 30, 2026
- [x] Added OmniStream APK download link to portfolio (redirects to GitHub Releases)
- [x] Set up release signing config for OmniStream (keystore + gradle config)
- [x] Moved signing credentials to local.properties (not pushed to GitHub)
- [x] Added .jks/.keystore to .gitignore
- [x] Planned OmniStream access gate (password + account creation)
- [x] Planned OmniStream Web — companion website with login and cross-device sync

### Day 3 — Jan 31, 2026
- [x] OmniStream Phase 9 (Download System) — complete with bug fixes
- [x] Fixed manga downloads: CDN was blocking direct requests, added proper image headers
- [x] Fixed video downloads: added HLS stream support (m3u8 playlist parsing + segment download)
- [x] Offline playback working for both manga chapters and video content
- [x] Chapter read status highlighting (greyed out read chapters, green checkmarks for downloads)
- [x] Floating batch download button, chapter number formatting cleanup
- [x] WorkManager foreground service fix for Android 14+ (foregroundServiceType in manifest)
- [x] Tested on Infinix Note 30 — downloads, offline reading, offline video all working

---

## All Live Links

| Project | Repo | Live |
|---------|------|------|
| Portfolio | [portfolio](https://github.com/TamerAli-0/portfolio) | [tamerali-0.github.io/portfolio](https://tamerali-0.github.io/portfolio/) |
| OmniStream | [OmniStream](https://github.com/TamerAli-0/OmniStream) | Android App (APK) |
| WeatherNow | [weather-now](https://github.com/TamerAli-0/weather-now) | [tamerali-0.github.io/weather-now](https://tamerali-0.github.io/weather-now/) |
| TypingArena | [typing-arena](https://github.com/TamerAli-0/typing-arena) | [tamerali-0.github.io/typing-arena](https://tamerali-0.github.io/typing-arena/) |
| SoundBoard | [sound-board](https://github.com/TamerAli-0/sound-board) | [tamerali-0.github.io/sound-board](https://tamerali-0.github.io/sound-board/) |
| PixelDraw | [pixel-draw](https://github.com/TamerAli-0/pixel-draw) | [tamerali-0.github.io/pixel-draw](https://tamerali-0.github.io/pixel-draw/) |

---

## Upcoming — OmniStream Expansion

### OmniStream Auth & Access Gate
- App will require an access password on first launch (provided by Tamer)
- After entering the password, users create a personal account (email + password)
- Account syncs across devices — download the app on a new phone, log in, pick up where you left off
- Tracks continue reading, continue watching, favorites, and preferences per account

### OmniStream Web (Planned)
- A companion website mirroring the app experience
- Login with the same account used in the Android app
- Continue reading/watching progress synced between app and web
- Browse library, manage favorites, and access history from any browser
- Same multi-source architecture, adapted for web

---

## Notes
- Each project gets its own GitHub repo
- Portfolio project cards will link to live demos + GitHub repos
- GitHub Pages or Vercel for hosting demos
- Update this devlog after each session
