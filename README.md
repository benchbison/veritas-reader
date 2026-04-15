# Veritas Reader

**v1.4.0**

A self-contained, offline-capable ebook reader. Single HTML file — no install, no server required.

**Live:** [benchbison.github.io/veritas-reader](https://benchbison.github.io/veritas-reader/)

---

## Formats

- EPUB (full parsing — cover art, inline images, table of contents)
- PDF (rendered page-by-page)
- MOBI / AZW / AZW3 (PalmDOC decompression, EXTH metadata)
- TXT (auto chapter detection)

## Features

- **Library** — drag and drop books, generated canvas covers, user cover override, progress tracking, continue reading shortcut
- **Paginated reader** — full-screen page layout, hard-cut page turns, tap zones, swipe navigation, keyboard support
- **Display** — font size, line spacing, reading margins, four typefaces, brightness slider, night mode
- **Annotations** — highlight in four colors, margin notes, long-press to copy, export to TXT or MD
- **Bookmarks** — add, browse, jump to position
- **TTS** — text-to-speech using device voices, speed/pitch control, sleep timer
- **Search** — find within chapter, navigate matches, cross-chapter results
- **Auto-scroll** — page-based continuous reading at adjustable speed
- **Reading goals** — daily minute target, streak tracker, weekly grid, library totals
- **PWA** — installs to home screen, works fully offline after first load

## Storage

All data stored locally in IndexedDB — books, progress, highlights, bookmarks, stats. Nothing leaves the device.

## Usage

Open `index.html` in any modern browser, or visit the GitHub Pages URL above. To install as an app on mobile: open in Chrome or Safari → Add to Home Screen.

---

## Changelog

### v1.4.0
- Paginated layout — full-screen page-by-page reading, no scrolling
- Hard-cut page turns with tap zones and swipe navigation
- Keyboard navigation (arrow keys, spacebar, F to toggle toolbar)
- Toolbar auto-hides; tap middle or any panel button to restore
- Auto-scroll converted to page-based interval turns
- Resume saves exact page within chapter
- Re-paginates on window resize and orientation change

### v1.3.0
- Continue reading banner on library screen
- In-book search with match highlighting and cross-chapter results
- Long-press highlight to copy text to clipboard
- Reading goals, daily streak tracker, weekly activity grid
- Library-wide stats (total time, sessions, books finished)

### v1.2.0
- Text highlights in four colors with margin notes
- Highlights panel with jump-to and export (TXT, MD)
- IndexedDB persistence — all data survives refresh
- PWA manifest and service worker for offline install
- Delete books from library

### v1.1.0
- Generated canvas covers for books without cover art
- User cover image override
- EPUB inline image extraction
- MOBI/AZW binary parser
- Renamed to Veritas Reader

### v1.0.0
- Initial release — EPUB, PDF, TXT, library, reader, TTS, bookmarks, night mode

---

*Built Slowly. Made to Last.*
