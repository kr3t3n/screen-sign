# Screen Sign

Turn any screen into a sign. Type your message, and it fills the display in the largest font that fits.

**Live demo:** [aithings.online/screen-sign](https://aithings.online/screen-sign/)

## What it does

- Displays text as large as possible to fill the entire screen
- Supports **bold**, *italic*, `code`, and headings via Markdown
- Auto-fits text size — or manually adjust with **+** / **-** buttons
- Minimal floating edit button stays out of the way
- Remembers your text between sessions (localStorage)
- Works on desktop and mobile
- Zero dependencies, single HTML file

## Use cases

- Conference name tags and table signs
- Store window messages
- Protest signs on a tablet
- Quick message to someone across the room
- Airport pickup signs
- Score displays

## How to use

1. Open `index.html` in any browser (or visit the [live demo](https://aithings.online/screen-sign/))
2. Tap the pencil icon (bottom-right)
3. Type your message
4. Tap the checkmark to go full-screen sign mode
5. Double-tap the display to re-open the editor

## Self-host

It's a single HTML file. Drop it anywhere:

```bash
# Copy to your web server
cp index.html /var/www/html/screen-sign/

# Or just open locally
open index.html
```

## License

MIT — do whatever you want with it.
