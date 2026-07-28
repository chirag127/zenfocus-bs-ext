# ZenFocus Browser Extension

[![GitHub stars](https://img.shields.io/github/stars/chirag127/zenfocus-bs-ext?style=flat-square)](https://github.com/chirag127/zenfocus-bs-ext)
[![License](https://img.shields.io/github/license/chirag127/zenfocus-bs-ext?style=flat-square)](LICENSE)
[![Release](https://img.shields.io/github/v/release/chirag127/zenfocus-bs-ext?style=flat-square)](https://github.com/chirag127/zenfocus-bs-ext/releases/latest)
[![GH Pages](https://img.shields.io/badge/site-live-brightgreen?style=flat-square)](https://chirag127.github.io/zenfocus-bs-ext/)

Pomodoro timer + task manager browser extension. MV3, Chrome/Edge/Firefox.

## Live Site

**https://chirag127.github.io/zenfocus-bs-ext/**

## Install

**From release (recommended):**
1. Download `zenfocus.zip` from [Latest Release](https://github.com/chirag127/zenfocus-bs-ext/releases/latest)
2. Extract the zip
3. Open `chrome://extensions/` and enable Developer Mode
4. Click "Load unpacked" and select the extracted `extension/` folder

**From source:**
```bash
git clone https://github.com/chirag127/zenfocus-bs-ext.git
# Load extension/ folder as unpacked extension
```

## Features

- Pomodoro timer with configurable duration (default 25 min)
- Desktop notification when session ends
- Task list with add/edit/delete (synced via chrome.storage.sync)
- Options page to customize timer
- No backend — all data stored locally

## Project Structure

```
extension/          <- Load this folder as unpacked extension
  manifest.json
  background.js     <- Service worker (timer logic)
  icons/icon.png
  popup/            <- Main UI
  options/          <- Settings page
docs/               <- GH Pages landing
```

## License

MIT
