# SlicerVR 2.0010 — ClipCut Timeline Editor

![SlicerVR Preview](./preview.png)

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
© 2026 Master Nytmaer / Brackuro Studios LLC
