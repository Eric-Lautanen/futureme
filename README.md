# Dear Future Me

**[Live demo →](https://eric-lautanen.github.io/futureme/)**

A private letter box for writing to your future self — seal a letter until a date you choose, or leave it open to reread anytime. Every letter also resurfaces on its own anniversary, so past-you pays present-you a small, unplanned visit each year.

No account. No server. No sync. Nothing to buy. It's a single HTML file that runs entirely in your browser.

## Why

Most journaling apps are built to be companies. This one is built to be a file. It will never be acquired, never add a subscription tier, and never phone home — because there's no home to phone. Your letters live in your browser's local storage, on your device, under your control.

## Getting started

Try it instantly at the [live demo](https://eric-lautanen.github.io/futureme/) — no download needed. Note that letters written there are stored in that browser only; for something you'll keep long-term, download your own copy instead:

1. Download `dear-future-me.html`
2. Open it in any modern browser (double-click, or drag it into a browser window)
3. That's it — no install, no build step, no internet connection required

Bookmark the file or keep it on your desktop. Opening it again picks up right where you left off, since your data is saved locally each time you write.

## Features

- **Write** — compose a letter with an optional title, mood, and tags
- **Choose when it opens** — leave it open to read anytime, or seal it for later using one-tap presets (1 week, 1 month, 6 months, 1/3/5/10 years, next birthday) or your own custom years/months/days combination
- **Sealed** — locked letters show only a countdown; there's no peeking before the date arrives
- **Delivered** — your inbox of unlocked letters, with a small wax-seal animation the first time you open one
- **On This Day** — letters automatically resurface on the anniversary of the day you wrote them, plus a preview of what's coming up in the next 60 days
- **Archive** — every letter you've ever written, searchable and filterable by tag
- **Export / import** — download a full JSON backup of your letters, or restore from one (merge or replace)
- **Light / dark mode**

## Your data

Everything is stored in your browser's `localStorage`, scoped to the file you opened. That means:

- It stays on this device, in this browser, and never leaves it
- Clearing your browser data, switching browsers, or moving to a new device will lose it **unless you've exported a backup**
- Use **Settings → Export backup** regularly, and keep the `.json` file somewhere safe (a synced folder, an external drive, wherever you'd keep something you don't want to lose)

There is intentionally no cloud sync. That tradeoff is the whole point — nothing here can be hacked, sold, or shut down remotely, but you're also the only backup system it has.

## Tech

- Single self-contained HTML file — HTML, CSS, and JavaScript all in one place
- No frameworks, no build tools, no dependencies, no external requests of any kind
- Works fully offline

## License

Free and open source. Do whatever you'd like with it — use it, fork it, change it, give it to someone who needs it.
