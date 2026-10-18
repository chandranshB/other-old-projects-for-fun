# ⚡ chandranshB's Arcade & Apps Universe

> A consolidated, unified portfolio merging **three repositories** into a single interactive playground ready for **GitHub Pages** deployment. Every project is 100% playable, openable, and interactive directly in the browser!

![GitHub Pages Deployment](https://img.shields.io/badge/Deployment-GitHub%20Pages-38bdf8?style=for-the-badge&logo=github)
![Tech Stack](https://img.shields.io/badge/Tech-Three.js%20%7C%20React%20%7C%20Tailwind%20%7C%20WebAudio-a855f7?style=for-the-badge)
![Status](https://img.shields.io/badge/Playable-100%25%20In--Browser-10b981?style=for-the-badge)

---

## 🌟 Merged Repositories

This project unifies and elevates three separate codebases created by [@chandranshB](https://github.com/chandranshB):

| Repository | Original Contents | Merged & Enhanced As |
| :--- | :--- | :--- |
| [**`other-old-projects-for-fun`**](https://github.com/chandranshB/other-old-projects-for-fun) | `face controlled 3D FPS.html`<br>`Image to PDF.py`<br>`Notepad.py`<br>`Phone number info.py` | 🎮 **Face Controlled 3D FPS** (with webcam + mouse aim & Web Audio SFX)<br>📄 **Image to PDF Studio** (client-side PDF maker + Python view)<br>📝 **Desktop Retro Notepad** (web editor + local auto-save + Python view)<br>📱 **Phone Intelligence Lookup** (live international validator + Python view) |
| [**`random-tuesday`**](https://github.com/chandranshB/random-tuesday) | `index.html` (Camera Photo Puzzle) | 🧩 **Sliding Photo Puzzle Arcade** (live camera snap, custom image upload, synthwave preset gallery, audio slide FX & confetti) |
| [**`ginomai`**](https://github.com/chandranshB/ginomai) | `index.html`<br>`leaveTracker/index.html`<br>`dvd/index.html` | 📅 **Attendance & Leave Tracker Pro** (React + Tailwind with Cupertino & Material themes, dark mode, custom target goals & projections)<br>📺 **DVD Screensaver Deluxe** (corner hit detection, celebration chimes, speed controls & motion blur trail) |

---

## 🎮 Playable Applications Catalog

### 1. 🎯 Face Controlled 3D FPS Shooter (`apps/face-fps/`)
- **Technology**: Three.js r128, MediaPipe FaceMesh, Web Audio API procedural synthesizer.
- **Features**:
  - **Dual Aiming System**: Aim by moving your head/face via webcam OR using smooth mouse/touch controls.
  - **Arcade Sound FX**: Procedurally synthesized laser blaster, enemy explosion, and game-over audio.
  - **High Score & Stats**: Real-time score counter, local high-score persistence, and dynamic weapon recoil crosshair.

### 2. 🧩 Sliding Photo Puzzle Arcade (`apps/photo-puzzle/`)
- **Technology**: HTML5 Canvas, MediaStream Camera API, Web Audio API.
- **Features**:
  - **3 Input Sources**: Snap a photo via webcam, upload any picture from your device, or choose from custom synthwave/galaxy canvas art presets.
  - **Adjustable Difficulty**: 3×3 (Easy), 4×4 (Classic), and 5×5 (Pro).
  - **Timer & Move Counter**: Live stopwatch, move tracker, target peek modal, and victory celebration fanfare.

### 3. 📅 Attendance & Leave Tracker Pro (`apps/leave-tracker/`)
- **Technology**: React 17, Tailwind CSS, Lucide SVG Icons.
- **Features**:
  - **Dual Design Engine**: Switch instantly between **Apple Cupertino (iOS)** and **Google Material You** themes.
  - **Smart Attendance Math**: Calculates how many classes you can safely bunk or how many you must attend to maintain your target (70%, 75%, 80%, 85%).
  - **Sarcastic Feedback**: Features the witty, humorous validation responses from the original repo.

### 4. 📺 DVD Screensaver Deluxe (`apps/dvd-screensaver/`)
- **Technology**: HTML5 Canvas, Web Audio API, CSS Animations.
- **Features**:
  - **Corner Hit Tracker**: Real-time bounce counter and celebration chime/banner when hitting an exact corner.
  - **Customizable**: Customize the bouncing text directly in the dock or via URL parameter (`?text=YourName`).
  - **Speed & Effects**: Speed controls (1x, 2x, Turbo), motion blur trails, and keyboard shortcuts (`H` to toggle UI).

### 5. 📄 Image to PDF Studio (`apps/image-to-pdf/`)
- **Technology**: Client-side `jsPDF`, Drag-and-Drop File API.
- **Features**:
  - **In-Browser Converter**: Drop multiple JPG/PNG images, set margins and page orientation, and download merged PDFs with 100% client-side privacy.
  - **Python Source Viewer**: Includes the original `Image to PDF.py` Tkinter script with copy button and `.py` download.

### 6. 📝 Desktop Retro Notepad (`apps/notepad/`)
- **Technology**: Pure Vanilla JavaScript, HTML5 LocalStorage, CSS Glassmorphism.
- **Features**:
  - **Full Window Simulation**: Desktop window frame with functional File and Edit dropdown menus.
  - **Productivity**: Auto-saves continuously to `localStorage`, exports to `.txt` and `.md`, prints, and counts words/characters in real-time.
  - **Python Source Viewer**: Includes the original `Notepad.py` Tkinter code with syntax display and `.py` download.

### 7. 📱 Phone Number Intelligence (`apps/phone-info/`)
- **Technology**: `libphonenumber-js` library.
- **Features**:
  - **Live Metadata Lookup**: Parses numbers to reveal country flag, national/international formats, E.164, line type, and estimated timezone.
  - **Preset Examples**: 1-click test numbers for India (+91), US (+1), UK (+44), Japan (+81), and Germany (+49).
  - **Python Source Viewer**: Includes the original `Phone number info.py` script with copy and download.

---

## 🚀 How to Deploy to GitHub Pages

### Method 1: GitHub Actions (Automated - Recommended)
1. Push this repository to GitHub under your account (e.g. `chandranshB/showcase` or your chosen name).
2. On GitHub, navigate to **Settings** &rarr; **Pages**.
3. Under **Build and deployment** &gt; **Source**, select **GitHub Actions**.
4. The workflow in `.github/workflows/deploy.yml` will automatically trigger and deploy your site to `https://<username>.github.io/<repo-name>/`!

### Method 2: Classic Branch Deployment
1. On GitHub, navigate to **Settings** &rarr; **Pages**.
2. Under **Source**, choose **Deploy from a branch**.
3. Select branch `main` (or `master`) and folder `/(root)`.
4. Click **Save**. Your site will be live within 1–2 minutes!

---

## 💻 Local Development

No build step, node modules, or compile steps required! Simply open `index.html` or run any lightweight local server:

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve .

# Or open index.html directly in any browser
```

Visit `http://localhost:8000` to explore the arcade hub!

---

## 📂 Repository Structure

```
chandransh-showcase/
├── .github/
│   └── workflows/
│       └── deploy.yml              # Automated GitHub Pages deployment
├── index.html                      # Master Hub Portal (Search, Filters, Modal runner)
├── README.md                       # Documentation & Project Guide
├── apps/
│   ├── face-fps/                   # Face Controlled 3D FPS game
│   │   └── index.html
│   ├── photo-puzzle/               # Sliding Photo Puzzle game
│   │   └── index.html
│   ├── leave-tracker/              # Attendance & Leave Tracker Pro
│   │   └── index.html
│   ├── dvd-screensaver/            # DVD Screensaver Deluxe
│   │   └── index.html
│   ├── image-to-pdf/               # Image to PDF converter & Python viewer
│   │   └── index.html
│   ├── notepad/                    # Desktop Retro Notepad & Python viewer
│   │   └── index.html
│   └── phone-info/                 # Phone Intelligence Lookup & Python viewer
│       └── index.html
└── original-source/                # Exact preserved source code from original repos
    ├── other-old-projects-for-fun/
    ├── random-tuesday/
    └── ginomai/
```

---

*Crafted with ❤️ by [chandranshB](https://github.com/chandranshB)*
