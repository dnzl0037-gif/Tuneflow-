# 🎵 TuneFlow

**Offline music player — your library, your device, your flow.**

TuneFlow is a single-file web app that plays your local audio files. No accounts, no uploads, no server. Works on GitHub Pages, any static host, or just by opening `index.html`.

## ✨ Features

- 🎧 Plays **MP3, WAV, OGG, M4A, FLAC, AAC, OPUS, WebM, WMA, AIFF, APE**
- 🖼️ Extracts **embedded thumbnails** (ID3v2 APIC, FLAC PICTURE, M4A covr)
- 📁 Folder picker + drag & drop
- 📱 Full **Media Session API** — lockscreen, Bluetooth, car, AirPods, smartwatch controls
- 🔀 Shuffle • Repeat (off / all / one) • Search • Volume • Seek
- 💾 Library saved in **IndexedDB** — persists offline
- ⌨️ Keyboard shortcuts: `Space` play/pause • `←/→` seek • `Shift+←/→` prev/next • `↑/↓` volume • `M` mute • `S` shuffle • `R` repeat
- 🎨 Black & red gradient theme with Poppins font

## 🚀 Deploy to GitHub Pages

1. Create a new repo on GitHub
2. Upload `index.html` and `README.md`
3. Go to **Settings → Pages**
4. Source: **Deploy from a branch** → `main` / `root`
5. Visit `https://<your-username>.github.io/<repo-name>/`

## 📦 Local usage

Just double-click `index.html` — no build, no install.

## 🔒 Privacy

Everything stays on your device. Audio files are never uploaded. Thumbnails are read from the file's embedded metadata.

## 📝 License

MIT — do whatever you want.