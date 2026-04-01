# ScanIt — Barcode Scanner PWA

A full-featured EAN-13 barcode scanner built for South Africa.
Scans product barcodes via your phone camera and looks up product info, nutritional data, and more.

---

## 🚀 Deploy to GitHub Pages (Free, takes ~3 minutes)

This is the **recommended way** — it gives you a permanent `https://` URL which is required for camera access on Android.

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up (free).

### Step 2 — Create a new repository
1. Click the **+** button → **New repository**
2. Name it: `scanit`
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the files
1. Click **uploading an existing file** on the new repo page
2. Drag and drop ALL 5 files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.svg`
   - `icon-512.svg`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)**
4. Click **Save**

### Step 5 — Open on your phone
After ~1 minute, your app will be live at:
```
https://YOUR-USERNAME.github.io/scanit
```

Open this URL in Chrome on your Android phone.
When you tap **Start Camera**, Chrome will ask for camera permission — tap **Allow**.

### Step 6 — Install as App (optional but great)
In Chrome on your phone:
- Tap the **⋮** menu → **Add to Home Screen**
- It'll appear as a real app icon with no browser chrome

---

## Features

- 📷 Live camera barcode scanning (ZXing — modern, fast)
- 🔦 Torch/flashlight toggle for dark shops
- 🔍 Dual data source lookup: UPCitemdb + Open Food Facts
- 🇿🇦 SA manufacturer recognition (Beacon, Tiger Brands, Clover, etc.)
- 🍎 Nutritional info + Nutri-Score for food products
- 💬 Share products via WhatsApp
- 📋 Scan history with date grouping (50 items)
- 📤 Export history to WhatsApp
- ⚙️ Sound + vibration settings
- 📲 Installable PWA (works offline for UI)

---

## Files

| File | Purpose |
|---|---|
| `index.html` | Full app (single file) |
| `manifest.json` | PWA metadata (name, icon, theme) |
| `sw.js` | Service worker (offline + caching) |
| `icon-192.svg` | App icon |
| `icon-512.svg` | App icon (large) |
