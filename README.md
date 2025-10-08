# Virtual Drum Kit — Studio Edition

Play a modern, studio-themed drum pad in your browser. Click pads or use your keyboard, record a groove, and play it back — all with polished visuals and fully synthesized Web Audio (no external samples).

## 🎮 Live Demo
- (After publishing with GitHub Pages, your link will look like)
  `https://YOUR_USERNAME.github.io/virtual-drum-kit/`

## ✨ Features
- 8 drum pads: Kick, Snare, Closed/Open Hi-Hat, Clap, 3 Toms
- Keyboard control: **A S D F G H J K**
- Recording + timeline visualization
- Playback with moving playhead
- 1/16 Quantize toggle
- Tempo control (tap **BPM** to +5)
- Polished, music-studio UI

## ⌨️ Shortcuts
- **A S D F G H J K** — trigger pads  
- **R** — start/stop recording  
- **Space** — play/stop playback  
- **C** — clear the current recording

## 🚀 Run locally
Just open `index.html` in Chrome/Edge/Firefox/Safari.
> First click/keypress “unmutes” audio due to browser policy.

## 🛠 Tech
- Vanilla HTML/CSS/JS
- Web Audio API (synth drums), DynamicsCompressor, simple reverb loop
- No frameworks, no build step

## 📦 Deploy to GitHub Pages
1. Create a repo named `virtual-drum-kit`.
2. Add `index.html` (this project), plus this `README.md`.
3. Push to `main`.
4. In GitHub: **Settings → Pages**  
   - **Source:** `Deploy from a branch`  
   - **Branch:** `main` and **/ (root)**  
5. GitHub builds a URL like `https://YOUR_USERNAME.github.io/virtual-drum-kit/`.

> If you don’t see it immediately, give Pages a minute to publish and refresh.

## 📱 Mobile tips
- iOS: ensure the device isn’t on Silent; tap once to enable audio.
- Android: tap once before playing; turn up media volume.

## 🔒 License
MIT — see `LICENSE`.
