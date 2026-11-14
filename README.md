# Exact JSON Viewer & Formatter

A Chrome extension that shows JSON as a clean, collapsible tree and keeps big numbers exact. Most viewers run your data through `JSON.parse`, which rounds `12345678901234567890` to `12345678901234567000`. This one shows what the server sent.

Free. No ads, no tracking, no network requests, no remote code. The only permission is `storage`, used for your theme.

## Features

- Collapsible tree; large arrays start collapsed so big files stay fast
- Exact big integers and decimals, with an "exact" badge where JavaScript would round
- Click any key to copy its path (for example `$.data.items[3].name`)
- Raw / Parsed toggle
- Copy formatted or minified JSON, with numbers kept exact
- Dark, light or auto theme
- Clickable http/https links
- Clear "Invalid JSON" message with line, column and the bad line marked

## Install (load unpacked)

1. Download `exact-json-viewer-1.2.0.zip` from the [latest release](../../releases/latest) and unzip it.
2. Open `chrome://extensions` in Chrome (or any Chromium browser such as Edge or Brave).
3. Turn on **Developer mode** (top right).
4. Click **Load unpacked** and pick the unzipped folder (the one that contains `manifest.json`).
5. Open any JSON URL. To view local `.json` files, open the extension's **Details** and turn on **Allow access to file URLs**.

You can also clone this repo and load its root folder the same way.

## Privacy

The extension collects no data and sends none. It makes no network requests.

## Feedback

Found a bug or want a feature? [Open an issue](../../issues).

## License

MIT. Made by Inder Studio.
