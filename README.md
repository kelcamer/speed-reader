# PDF Speed Reader

Paste a PDF link (or pick/drop a file) → text is extracted with [pdf.js](https://mozilla.github.io/pdf.js/), copied to your clipboard, and loaded into an RSVP-style speed reader.

- Adjustable speed (100–1000 wpm) and text size, with focus-letter highlighting
- Longer pauses at punctuation and long words
- Play/pause, ±1 / ±10 word jumps, scrub bar, time remaining
- Keyboard: Space = play/pause, ←/→ = ±10 words, ↑/↓ = speed
- Editable extracted text, "Copy again" button, or paste plain text directly

## Use
Live at https://kelcamer.github.io/speed-reader/. Or open `index.html` in a browser. Pushes to `main` deploy via GitHub Pages (Settings → Pages → Source: GitHub Actions).

## Notes
- Some sites block cross-origin downloads; the app retries via public CORS proxies. For private PDFs, use the file picker so nothing leaves your device.
- Scanned (image-only) PDFs have no text layer and won't extract.
