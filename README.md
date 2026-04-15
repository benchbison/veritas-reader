# Veritas Reader

A self-contained, offline-capable ebook reader. Single HTML file — no install, no server required.

**Live:** [benchbison.github.io/veritas-reader](https://benchbison.github.io/veritas-reader/)

---

## Formats

- EPUB (full parsing — cover art, inline images, table of contents)
- PDF (rendered page-by-page)
- MOBI / AZW / AZW3 (PalmDOC decompression, EXTH metadata)
- TXT (auto chapter detection)

## Features

- **Library** — drag and drop books, generated canvas covers for books without cover art, user cover override, progress tracking
- **Reader** — warm paper aesthetic, Playfair Display / Crimson Pro typography, justified text
- **Display** — font size, line spacing, page width, four typefaces, brightness slider, night mode
- **Annotations** — highlight in four colors, margin notes, export to TXT or MD
- **Bookmarks** — add, browse, jump to position
- **TTS** — text-to-speech using device voices, speed/pitch control, sleep timer
- **Search** — find within chapter, navigate matches, cross-chapter results
- **Auto-scroll** — continuous scroll at adjustable speed
- **Swipe navigation** — swipe left/right to change chapters on mobile
- **Reading goals** — daily minute target, streak tracker, weekly grid, library totals
- **Continue reading** — one-tap resume from library screen
- **PWA** — installs to home screen, works fully offline after first load

## Storage

All data stored locally in IndexedDB — books, progress, highlights, bookmarks, stats. Nothing leaves the device.

## Usage

Open `index.html` in any modern browser, or visit the GitHub Pages URL above. To install as an app on mobile: open in Chrome or Safari → Add to Home Screen.

---

*Built Slowly. Made to Last.*
