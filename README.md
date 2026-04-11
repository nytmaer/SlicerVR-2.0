# SlicerVR 2.0007
**ClipCut Timeline Editor** — Trim and export videos directly in your browser. No installs, no uploads, no accounts.

Built for Meta Quest 3, works everywhere.

---

## Quick Start

1. **Drop a video** onto the upload area (MP4, WebM, or MOV)
2. **Drag the handles** on the timeline to set your in and out points
3. **Pick a format** — WebM (fastest), MP4, or GIF
4. **Hit Export** — your clip downloads automatically

---

## Controls

| Button | Action |
|--------|--------|
| ▶ Play | Play / pause |
| ⏮ Start | Jump to trim start |
| ⏭ End | Jump to trim end |
| ↺ Reset | Clear trim points |
| ✂️ Export | Export your clip |

**Keyboard:** `Space` to play/pause · `[ ]` to jump to start/end · `← →` to step through frame by frame

---

## Export Formats

- **WebM** — fastest, best for web sharing
- **MP4** — best device compatibility (requires MediaBunny to load)
- **GIF** — looping animation, max 10 seconds

---

## Notes

- Everything runs locally in your browser — your video never leaves your device
- After exporting, **Share** and **Save** buttons appear for sending directly from Quest or mobile
- Requires HTTPS when hosted remotely (Quest browser requirement)

---

## License

MIT License — Copyright © 2026 Brackuro Studios LLC

☕ [Support on Ko-fi](https://ko-fi.com/nytmaer) · 📺 [Watch the demo](https://youtu.be/xiR531CFzqo)# SlicerVR 2.0010 — ClipCut Timeline Editor

![SlicerVR Preview](./screenshot.png)

**Fast, browser-based video trimming with zero uploads. Built for creators, devs, and VR workflows.**

---

## 🚀 Overview

SlicerVR is a lightweight, client-side video trimming tool that runs entirely in the browser.

Drop a video → trim → export.

No installs. No uploads. No waiting.

---

## ✨ Features

* ✂️ Drag-based ClipCut timeline editor
* 🎯 Snap-to-grid precision trimming
* 🎬 Export formats:

  * WebM (fast)
  * MP4 (when supported)
  * GIF (short clips)
* ⚡ Adaptive export engine (MediaBunny + fallback)
* 🎚 Quality presets (Low / Balanced / High)
* 📱 Mobile + touch support
* 🔐 Fully local processing (no uploads)

---

## 🖼 Interface Preview

### 🎬 Video Stage

```text
┌───────────────────────────────┐
│           VIDEO               │
│        ▶ Play Overlay         │
└───────────────────────────────┘
```

* Responsive 16:9 container
* Overlay play button
* Clean viewing stage

---

### ✂️ ClipCut Timeline

```text
|---- Trimmed ----|==== Selected ====|---- Trimmed ----|
0%              Start              End              100%
```

* Drag handles (left/right)
* Move entire selection window
* Snap-based trimming for precision

---

### 🎚 Time + Selection Info

```text
Start: 00:00     →     End: 00:10
Selected Duration: 00:10
```

* Live updating trim values
* Clear duration feedback

---

### 🎛 Controls

```text
[▶ Play] [⏮ Start] [⏭ End] [↺ Reset]
[✂️ Export] [📤 Share] [💾 Save] [📁 New]
```

* Playback controls
* Reset trimming
* Export + sharing options

---

### 📊 Export + Info Panel

```text
Original Duration: 00:45
Trim Start:        00:05
Trim End:          00:15
Export Size:       00:10
```

* Real-time clip stats
* Clear export expectations

---

## 🔐 Safety & Stability

SlicerVR is designed for safe browser usage:

* ✅ File type validation (MP4, WebM, MOV)
* ✅ File size limits (prevents crashes)
* ✅ Export duration limits
* ✅ Safe object URL cleanup
* ✅ No external uploads or tracking

All processing is done locally.

---

## 🧠 How It Works

1. Load a video file
2. Adjust trim handles or drag selection
3. Snap to precise cut points
4. Export clip instantly

---

## ⚙️ Tech Stack

* HTML5 / CSS3 / JavaScript
* Canvas API (frame rendering)
* MediaRecorder API
* MediaBunny (advanced encoding)
* gifenc (GIF generation)

---

## 📦 Installation

```bash
git clone https://github.com/your-repo/slicervr-2.0.git
cd slicervr-2.0
open index.html
```

Or deploy via GitHub Pages.

---

## 🧪 Supported Formats

| Input | Output          |
| ----- | --------------- |
| MP4   | WebM, MP4*, GIF |
| WebM  | WebM, GIF       |
| MOV   | WebM, MP4*      |

* Depends on browser support

---

## ⚠️ Limitations

* GIF export limited to short durations
* Large files depend on device memory
* MP4 export varies by browser

---

## 🛣 Roadmap

* 🎯 Frame-by-frame editing
* 🔍 Zoomable timeline
* 🔊 Real waveform visualization
* 📦 Batch export queue
* 🎥 Creator presets (TikTok / YouTube / VR)

---

## ☕ Support

Support development:

👉 https://ko-fi.com/nytmaer

---

## 🔥 Vision

SlicerVR is a fast, modular content slicing engine.

Built to plug into creator pipelines, VR workflows, and automated publishing systems.

---

## 📄 License

MIT License
© 2026 Nytmaer / Brackuro Studios LLC
