# 3tz

A tiny browser extension popup that lets users type a 3-digit US area code and instantly see a simplified timezone result: `EST`, `CST`, `MST`, `PST`, or `Unknown`.

## Files

- `manifest.json` — Manifest V3 extension config with a popup entry point.
- `popup.html` — Small popup UI with one input and one result line.
- `popup.css` — Lightweight styling for the popup.
- `popup.js` — Static area-code-to-timezone mapping and instant lookup logic.

## Usage

1. Load the folder as an unpacked extension in a Chromium-based browser.
2. Open the extension popup.
3. Type the first 3 digits of a US phone number.
4. Read the matching timezone.

If the area code is not in the static map, the popup shows `Unknown`.
