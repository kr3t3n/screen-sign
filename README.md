<p align="center">
  <img src="favicon.svg" alt="Screen Sign" width="80" />
</p>

<h1 align="center">Screen Sign</h1>

<p align="center">
  <strong>Turn any screen into a sign.</strong><br />
  Type your message and it fills the display as large as possible.
</p>

<p align="center">
  <a href="http://aithings.online/screen-sign/">Live Demo</a>
</p>

---

<p align="center">
  <a href="http://aithings.online/screen-sign/">
    <img src="screenshot.png" alt="Screen Sign — Hello World!" width="720" />
  </a>
</p>

## Features

- **Auto-fitting text** — fills the entire screen in the largest font that fits
- **Markdown support** — **bold**, *italic*, `code`, headings
- **Manual font size** — adjust with floating + / - buttons
- **Paste from clipboard** — one-tap paste to replace current text
- **Customisable** — text colour, background colour, font, weight, alignment, line height
- **Installable** — works as a PWA on iOS, Android, and desktop
- **Remembers everything** — text and settings persist in localStorage
- **Zero dependencies** — single HTML file, no build step

## Use Cases

- Conference name tags and table signs
- Store window messages
- Airport pickup signs
- Quick message to someone across the room
- Score displays
- Protest signs on a tablet

## How to Use

1. Open the [live demo](http://aithings.online/screen-sign/) or `index.html` locally
2. Tap anywhere on the screen to open the editor
3. Type your message (supports markdown)
4. Tap the screen again to close the editor
5. Use the gear icon to customise colours, fonts, and alignment

## Self-Host

It's a single HTML file. Drop it anywhere:

```bash
cp index.html /var/www/html/screen-sign/
```

Or just open it directly in your browser.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Vanilla HTML/CSS/JS |
| Rendering | CSS Flexbox + binary search font fitting |
| Storage | localStorage |
| PWA | Web App Manifest + Apple touch icon |
| Dependencies | None |

## License

MIT — do whatever you want with it.

---

<p align="center">
  <a href="https://x.com/georgipep"><img src="https://img.shields.io/badge/Follow%20on%20X-000000?style=for-the-badge&logo=x&logoColor=white" alt="Follow on X"></a>
  &nbsp;
  <a href="https://buymeacoffee.com/georgipep"><img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" alt="Buy Me a Coffee"></a>
</p>
